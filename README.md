BookRa1n

BookRa1n is an open-source research tool for exploring security behavior on A12 devices using the publicly disclosed vulnerability CVE-2025-43471.

Apple CVE Reference: https://support.apple.com/en-ca/125634

Raw project source: https://github.com/rhcp011235/A12_Bypass_OSS

This project supports security researchers, digital forensics analysts, and the SetupA12 community in studying system-level mechanisms on modern iOS devices.

Features

Research-oriented implementation for studying A12 device boot behavior

Demonstrates effects of CVE-2025-43471 in controlled environments

Modular and transparent codebase for academic analysis

Fully open-source for reproducibility

About CVE-2025-43471

CVE-2025-43471 is a publicly documented vulnerability affecting certain A12-based devices under specific conditions.
This repository does not provide or promote any illegal bypassing techniques. Its purpose is to support researchers in:

Understanding the vulnerability’s behavior

Testing defensive or mitigative strategies

Studying iOS device trust and boot chains

Expanding community knowledge on A12 hardware security

For technical details, refer to Apple's official disclosure.

Build & Development

This project is intended for research use. The build process focuses on code inspection and experimentation.

git clone https://github.com/rhcp011235/A12_Bypass_OSS
cd A12_Bypass_OSS
# Modify, inspect, or integrate into your research workflow


No prebuilt binaries are provided to prevent misuse.

Repository Structure
/src
    Core implementation and research components
/docs
    Technical notes and references
/tools
    Utilities for debugging and analysis
LICENSE
README.md

Credits

Special thanks to:

The SetupA12 community for discussions and support

Independent researchers and exploit analysts whose work inspired this project

Disclaimer

This tool is provided strictly for educational, academic, and authorized security research purposes only.

The authors do not endorse unauthorized device unlocking, bypassing, or any illegal activity.

Use this software only on devices you own or are permitted to analyze.

The authors are not responsible for any damage, data loss, or misuse of this software.

By using this project, you agree to comply with all applicable laws and ethical guidelines.

License

Released under the MIT License. Researchers are free to study, modify, and extend the code while maintaining responsibility for its use.
