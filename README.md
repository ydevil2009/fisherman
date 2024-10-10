# fisherman
This Python script is designed for Wi-Fi network scanning and password cracking using a brute-force dictionary attack, leveraging the pywifi library.

Wi-Fi Scanning:
The script first scans for available Wi-Fi networks. It initializes a Wi-Fi interface, starts the scan, and displays the networks in order of signal strength. The user can view details like network names (SSIDs) and signal levels.

Password Cracking:
Once a Wi-Fi network is selected, the script attempts to crack the password using a brute-force dictionary attack. It reads potential passwords from a file, creates a Wi-Fi profile for the target network, and attempts to connect using each password. If the correct password is found, the connection is successful, and the password is displayed.

Security Note:
The script demonstrates how Wi-Fi connections work and provides an example of a brute-force attack. However, unauthorized use of this code to crack Wi-Fi passwords is illegal. It should only be used for educational purposes or on networks you have permission to access.
