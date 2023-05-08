# RapidPass
This is a simple command-line tool for Windows that generates a random password of a given length. The password can include uppercase and lowercase letters, digits, and punctuation symbols.

- No passwords are stored anywhere
- Quick and easy to generate

## Installation
**Rebuild**:
You need to have Python 3 installed on your system. You can download Python from the official website: https://www.python.org/downloads/
- Run `pip install -r requirements.txt`
- Run `pyinstaller --clean --onefile RapidPass.py`

**Standalone executable**
To use the executable, add the directory containing the executable to your system's environment variables:

- Open the Start menu and search for "Environment Variables."
- Click "Edit the system environment variables."
- Click the "Environment Variables" button.
- Under "System Variables," scroll down and click on "Path," then click "Edit."
-  Click "New" and enter the full path to the directory containing the script, e.g., "..\path\to\RapidPass.exe"
- Click "OK" to close all the windows.
Now you can run the script from any directory in the command prompt by typing "RapidPass".

## Usage
To generate a password with the default length of 32 characters, simply run the script:
`RapidPass`

You can also specify the length of the password as a command-line argument:
`RapidPass 16`

This will generate a password with 16 characters.

The script will output the generated password to the console.

## License
This script is released under the MIT License. See the LICENSE file for details.

## Disclaimer
This script is provided for educational and demonstration purposes only. It may not be suitable for generating secure passwords for critical applications. Use at your own risk.