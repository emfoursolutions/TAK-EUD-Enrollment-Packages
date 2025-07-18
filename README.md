# Mission Packages for ATAK and WinTAK - Auto Enrollment

## Overview
This repository contains **Mission Packages** for **ATAK** (Android Team Awareness Kit) and **WinTAK** that enable **automatic enrollment** onto a TAK Server. These packages streamline the configuration process, ensuring users can quickly connect to the TAK infrastructure with minimal manual setup.

## Features
- **Automatic TAK Server Enrollment**: Simplifies the onboarding process for new users.
- **Preconfigured Server Settings**: Ensures correct server address, ports, and authentication settings.
- **Support for TLS Certificates**: Includes necessary CA certificates for secure communication.
- **Compatible with ATAK and WinTAK**: Works across multiple TAK platforms.
- **Map Streaming Sources**: Includes basic streaming services for various mapping providers

## Installation

1. Clone the repository and copy your Truststore.p12 file into the **certs** directory. 
2. Modify the **autoEnroll.pref** and insert your Server FQDN/IP, Port and Truststore Password
3. Zip the contents of the directory. Ensure the the contents are in the root directory.
4. Copy the ZIP file to your respective EUD

### ATAK (Android)
1. Download the **ATAK Mission Package** from the [Releases](https://github.com/emfoursolutions/TAK-EUD-Enrollment-Packages/releases) page.
2. Copy the `.zip` file to your Android device.
3. Open **ATAK** and navigate to `Settings` → `Mission Packages`.
4. Tap **Import** and select the downloaded package.

### WinTAK (Windows)
1. Download the **WinTAK Mission Package** from the [Releases](https://github.com/emfoursolutions/TAK-EUD-Enrollment-Packages/releases) page.
2. Open **WinTAK** and go to `Settings` → `Import Mission Package`.
3. Select the downloaded package and apply the settings.

## Troubleshooting
- **Certificate Errors**: Ensure the CA certificate is correctly installed on your device.
- **Connection Issues**: Verify network settings and ensure the TAK Server is reachable.
- **Missing Settings**: Re-import the mission package and restart the application.

## Contributing
We welcome contributions! If you'd like to improve the mission packages or add support for other TAK platforms, please submit a pull request.

## License
This project is licensed under the [GPLv3 License](LICENSE).

## Contact
For support or inquiries, please open an issue on GitHub or contact `support@example.com`.

---

### **Disclaimer**
These mission packages are provided "as-is" without any warranties. Ensure compliance with your organization's security policies before deployment.

