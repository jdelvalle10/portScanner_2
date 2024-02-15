# TCP Port Scanner

This is a simple TCP port scanner written in Python, using the `socket` and `IPy` libraries.

## How to Use

### Prerequisites
- Python 3.x installed on your system.

### Installation
1. Clone this repository to your local machine:
git clone https://github.com/your-username/tcp-port-scanner.git
2. Navigate to the directory containing the cloned repository:

cd tcp-port-scanner

bash
Copy code

### Usage

Run the script with the following command:

python port_scanner.py <target> <start_port> <end_port>

typescript
Copy code

Replace `<target>` with the target IP address or hostname to scan.
Replace `<start_port>` with the starting port number of the range to scan.
Replace `<end_port>` with the ending port number of the range to scan.

For example:

python port_scanner.py 192.168.1.1 1 1000
This command will scan ports 1 through 1000 on the host with IP address 192.168.1.1.

## Features

- Scans a range of TCP ports on a specified target.
- Prints out which ports are open and closed.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Feel free to customize the content and formatting as needed for your project.
