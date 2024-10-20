## MAC Changer

This Python script allows users to change the MAC (Media Access Control) address of a specified network interface. It can be useful for privacy, testing, or bypassing MAC address filtering.

### Features

- **Modify MAC Address**: Change the MAC address of a specified network interface to a user-defined value.
- **Verification**: Checks and confirms whether the MAC address has been successfully changed.
- **User-Friendly Options**: Simple command-line interface to specify the network interface and desired MAC address.

### Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Daniel-Ikenna/mac_changer
   ```

2. **Navigate to the Directory**

   ```bash
   cd mac_changer
   ```

3. **Run the Script**

   To change the MAC address:

   ```bash
   sudo python mac_changer.py -i <interface> -m <new_mac_address>
   ```

   Example:

   ```bash
   sudo python mac_changer.py -i eth0 -m 00:11:22:33:44:55
   ```

### Sample Output

```bash
Current MAC = 08:00:27:6b:4e:1a
[+] Changing MAC address for eth0 to 00:11:22:33:44:55
[+] MAC address was successfully changed to 00:11:22:33:44:55
```

### Requirements

- **Python 3.x**
- **Linux Operating System** (the script uses `ifconfig`, which is commonly available on Linux)
- **Superuser Privileges**: Running the script requires administrative permissions (use `sudo`).

### Important Note

Ensure you have the necessary permissions to modify the network interface settings. Changing the MAC address could disrupt your network connection, so proceed with caution.

### Author

[Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
[Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
