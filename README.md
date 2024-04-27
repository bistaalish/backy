# Proxmox Template Comparison and Upload Script

## Overview
This Python script is designed to compare Proxmox templates and upload them to Mega if they do not already exist in the Mega cloud storage. It helps automate the process of ensuring that the latest templates are available in the Mega cloud storage for convenient access.

## Requirements
- Python 3.x
- Mega SDK (Python package for interacting with Mega cloud storage)

## Installation
1. Install Python 3.x if not already installed. You can download it from [python.org](https://www.python.org/downloads/).
2. Install the Mega SDK Python package. You can install it using pip:
    ```bash
    pip install mega.py
    ```

## Usage
1. **Configuration**: 
   - Edit the script to provide your Proxmox server credentials and Mega cloud storage credentials. Ensure that you have necessary permissions to access Proxmox and Mega.
   - Optionally, customize the script according to your specific requirements, such as the path to store templates locally, etc.
2. **Run the Script**:
   - Execute the script using Python:
     ```bash
     python proxmox_template_comparison_and_upload.py
     ```
3. **Follow the Prompts**:
   - The script will prompt you to authenticate with your Proxmox server if necessary.
   - It will then compare the templates on your Proxmox server with those already uploaded to Mega.
   - If any new templates are found on the Proxmox server, the script will upload them to Mega.

## Important Notes
- Ensure that you have sufficient bandwidth and storage space on your Mega account for uploading the templates.
- This script assumes a stable internet connection for accessing both the Proxmox server and the Mega cloud storage.

## Disclaimer
This script is provided as-is without any warranty. Use it at your own risk. Make sure to review and understand the code before running it, especially if dealing with sensitive data.

## Author
[Your Name]

## License
[Specify the license under which the script is distributed, e.g., MIT License, GPL, etc.]
