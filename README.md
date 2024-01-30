# PsyFlood - An Advanced DDoS Tool

## Introduction

PsyFlood is an advanced DDoS (Distributed Denial of Service) tool written in Python using sockets. It allows users to launch DDoS attacks on a specified host, providing options to customize the attack parameters.

## Getting Started

1. **Clone the Repository:**
   ```shell with git (linux or windows)
   git clone https://github.com/your-username/psyflood.git
   cd psyflood

2. **Install the Requirements:**
   ```shell
   pip install -r requirements.txt
   
3. **Run the Sript:**
   ```shell
   python psyflood.py

## Usage
PsyFlood provides a simple command-line interface with various commands to configure and initiate DDoS attacks.
## Commands
**help:**
Display the help menu with the following command... ;)
  ```shell
  help
```
**host:**
Set the target host's domain or IP address.
  ```shell
  host example.com
```
**port:**
Set a custom port for the attack (optional, default is 80).
  ```shell
  port 8080
```
**attacks:**
Set the number of simultaneous attack threads (optional, default is 1000).
  ```shell
  attacks 500
```
**start:**
Start the DDoS attack with the configured parameters.
  ```shell
  start
```
## Disclaimer
Usage of PsyFlood for malicious purposes is strictly prohibited. Ensure that you have the legal right to perform any testing or DDoS activities. The author and contributors are not responsible for any misuse or damage caused by this tool. Use it responsibly and ethically.

## Author
l-urk · ハッカーL Hakkā L
```
GitHub: github.com/l-urk
```
## Contributions
Mr.Robot aka The White Rose, discord marzipan1476. Created the banner and added improvements to the code.

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details. (Will update this later)

## Excerpt
Excerpt by NaomAi...
"Psyflood is a Python script that utilizes multiple processes to simultaneously attack a target system via a distributed denial-of-service (DDoS) attack. It uses the PscyhoPy library to create multiple processes to simultaneously create requests, essentially overloading the target's network with too many requests to handle. The script is designed to be easy to use and requires minimal input from the user, while providing a powerful and effective means of attack. So, let the flooding begin, and have fun!"
