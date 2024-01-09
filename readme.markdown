
## Setup

This Python keylogger is designed for educational purposes only. It can be used to learn about keylogging techniques and should not be used for malicious activities.

1. Install the required library:

   ```bash
   pip install keyboard
   ```

2. Clone the repository:

   ```bash
   git clone https://github.com/pyloggs/python-keylogger.git
   ```

3. Navigate to the project directory:

   ```bash
   cd python-keylogger
   ```

4. Edit the script to add your email credentials and configure reporting preferences.

5. Run the keylogger:

   ```bash
   python keylogger.py
   ```

## Configuration

* **SEND_REPORT_EVERY:** Interval (in seconds) for reporting keylogs. Default is 60 seconds.
* **EMAIL_ADDRESS:** Your Gmail email address for email reporting.
* **EMAIL_PASSWORD:** Generate an "App Password" for secure email login. Enable two-factor verification on your Gmail account and generate a unique app password for this keylogger.
    1. Go to your Google Account settings: [My Account](https://myaccount.google.com/).
    2. Navigate to "Security" and enable "2-Step Verification."
    3. Under "Signing in to Google," select "App passwords."
    4. Choose "Mail" as the app and "Other (Custom Name)" for the device.
    5. Click "Generate" to get the app password.
    6. Use the generated app password as the value for **EMAIL_PASSWORD** in the script.
* **report_method:** Set to "email" for email reporting or "file" for local file reporting.

## Disclaimer

This keylogger is intended strictly for educational purposes related to learning about cybersecurity and cybercrime prevention. It is designed to help users understand keylogging techniques and improve their awareness of potential security vulnerabilities. Under no circumstances should this software be used for malicious purposes or to harm individuals, violate their privacy, or engage in any unethical activities.

The author explicitly disclaims any responsibility for the misuse of this software. Users are advised to adhere to ethical standards and legal regulations in their respective jurisdictions. Unauthorized use of this keylogger for harmful or malicious activities is strictly prohibited.

## Legal Notice

Please be aware that engaging in unauthorized access to computer systems, unauthorized monitoring of computer activities, and any other activities that violate privacy laws or regulations may result in severe legal consequences.

Always ensure that you have the explicit consent of individuals before using any form of monitoring or keylogging software. Be aware of and comply with local and international laws governing the use of such tools.

Use this software responsibly and in accordance with ethical standards and legal requirements.

## License

This project is licensed under the MIT License - Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Happy Coding!
