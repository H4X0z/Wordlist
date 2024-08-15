# Amazing Wordlist for Fuzzing by OrwaGodfather

## Usage

### 1. Install the `ffuf` Tool

To get started, you need to install the `ffuf` tool by running the following command:

```bash
go install github.com/ffuf/ffuf/v2@latest

```
### 2. Fuzzing Files & Directories

* Use this command to fuzz files and directories:
```bash
ffuf -w fuzz1337.txt -u "http://yourtarget.com/cgi-bin/dmt/FUZZ"
```
### 3.Fuzzing Parameters
To fuzz parameters, run the following command:
```bash
ffuf -w My-WordLISTs-main/param.txt -u "http://yourtarget.com/cgi-bin/dmt/?FUZZ=1337"
```
