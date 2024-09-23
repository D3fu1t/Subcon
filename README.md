# Overview

Subcon is a fast and effective command-line utility designed for security professionals and penetration testers.This tool automates the process of discovering subdomains Associated with a given Domain.


# Features
Multi-Source Enumeration: Utilizes multiple sources for subdomain discovery, including:

Subfinder: A popular subdomain discovery tool that efficiently finds subdomains.
crt.sh: A certificate transparency log that provides a wealth of information about registered domains and their subdomains.

Output Management: Outputs the discovered subdomains to a specified file, allowing for easy review and further analysis.

User-Friendly Interface: Simple command-line interface with clear usage instructions.

Customizable Output: Option to specify the output file name, making it flexible for different workflows.

# Installation 

### Oneliner Install for Linux 
> wget https://raw.githubusercontent.com/D3fu1t/Subcon/refs/heads/main/subcon;chmod +x subcon;mv subcon /usr/bin

## Others :

> git clone https://github.com/D3fu1t/Subcon.git
>
>  cd Subcon
>
> bash subcon example.com
# OR
> Copy/Move subcon to your Bin Directory.Then Use it like that :
>
> subcon example.com 

# Usage
To use Subcon Tool, run the following command in your terminal:

> subcon example.com [-o output_file]

# Parameters

-o output_file: (Optional) Specify a custom output file name for the results. Defaults to subdomains.txt

# Requirements
Bash shell
subfinder installed on your system
curl for fetching data from the web
jq for processing JSON output

Ensure you have the required tools installed (subfinder, curl, jq).

> sudo apt install subfinder
> 
> sudo apt install curl
> 
> sudo apt install jq

# License
This project is licensed under the MIT License. See the LICENSE file for details.
