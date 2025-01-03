# ONETYPE
THIS IS A TOOL WHICH IS 11 OTHER TOOLS COMBINATION FOR SCANNING AND RECON. THIS IS MADE FOR TIME SAVING AND CLI LOVER. ALL SCAN AND TEST REZULT ARE SAVED IN OUTPUT DIRECTORY WHICH IS MADE BY ITSELF. AND ALSO WHERE THE REZULTS AND SCAN TEXT FILES ARE SAVED IT TOLD US ON EXCUTING TIME.  
# OneType Tool

## Description

OneType is a comprehensive network reconnaissance tool designed for security professionals and enthusiasts. It automates the process of gathering information about a specified domain through various command-line utilities. By leveraging tools like `nslookup`, `whois`, `nmap`, and more, OneType provides a streamlined approach to perform reconnaissance, vulnerability scanning, and subdomain enumeration, all while saving the results in an organized manner.

## Features

- **DNS Information Gathering**: Utilizes `nslookup`, `host`, `dig`, and `dnsrecon` to collect detailed DNS records and information about the target domain.
- **Whois Lookup**: Retrieves registration details of the domain, including owner information and registration dates.
- **Subdomain Enumeration**: Identifies subdomains associated with the target domain using `assetfinder`.
- **Vulnerability Scanning**: Performs security assessments using tools like `nikto`, `wapiti`, and `wig` to identify potential vulnerabilities in web applications.
- **Network Scanning**: Uses `nmap` to discover services, operating systems, and open ports on the target domain.
- **Output Management**: Saves all results in a dedicated "output" directory for easy access and analysis.

## Requirements

Before using OneType, ensure you have the following tools installed on your system:

- Python 3.x
- `nslookup`
- `host`
- `whois`
- `dig`
- `wig`
- `nmap`
- `assetfinder`
- `wapiti`
- `dnsrecon`
- `dnsenum`
- `nikto`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ULTIMATRIX-pro/onetype.git
   cd onetype
   chmod +777 onetype
   chmod +x setup
   ./setup
   ./onetype
   ```

2. Ensure all required tools are installed on your system.

# Usage

1. Run the script:
   ```bash
   ./onetype.py
   ```

2. When prompted, enter the domain name you wish to investigate:
   ```
   【ENTER THE DOMAIN NAME】: example.com
   ```

3. Follow the prompts to enter the URL for vulnerability scanning:
   ```
   【ENTER THE URL OF DOMAIN】: https/http://example.com
   ```

4. The tool will execute various scans and save the results in the "output" directory. You will see messages indicating the progress and completion of each scan.

## Output

All results will be saved in the "output" directory with the following files:

- `nslookup-rezult.txt`: Results from the `nslookup` command.
- `host-rezult.txt`: Results from the `host` command.
- `whois-rezult.txt`: Results from the `whois` lookup.
- `dig-rezult.txt`: Results from the `dig` command.
- `wig-rezult.txt`: Results from the `wig` scan.
- `nmap-rezult.txt`: Results from the `nmap` scan.
- `subdomains-rezult.txt`: Results from the subdomain enumeration.
- `dnsrecon-rezult.txt`: Results from the `dnsrecon` scan.
- `dnsenum-rezult.txt`: Results from the `dnsenum` scan.
- `nikto-rezult.txt`: Results from the `nikto` scan.

## Ethical Considerations

**Important**: Always ensure you have explicit permission to perform scans and gather information about a domain. Unauthorized scanning can be illegal and unethical. Use this tool responsibly and in compliance with applicable laws and regulations.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the repository URL, license, and any other details to fit your specific project needs!
