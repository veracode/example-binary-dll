# [:] Example with DLL file

An example containing a Windows DLL file for demonstrating binary scan.

## Install and activate SourceClear
Follow the instructions in [Setting Up Veracode Agent-Based Scan](https://help.veracode.com/reader/hHHR3gv0wYc2WbCclECf_A/t9Dav~Bju~GJGoKWKe1WKA) to install and activate the CLI scan agent.

## Scan this project
There are 2 ways to scan this project.

### 1. Using url option
`srcclr scan --url https://github.com/srcclr/example-binary-dll`

### 2. On local path
```
1. git clone https://github.com/srcclr/example-binary-dll
2. cd example-binary-dll
3. srcclr scan .
```
