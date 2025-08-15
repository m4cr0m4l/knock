# knock
This shell script is designed for performing port knocking, a security technique used to secure access to a network service by requiring a specific sequence of connection attempts to designated ports. The script utilizes nmap to send packets to specified ports on a target host, allowing for both TCP and UDP protocols.

## Usage
```
usage: ./knock [options] <host> <port[:proto]> [port[:proto]] ...
options:
  -u, --udp             make all ports hits use UDP (default is TCP)
  -d, --delay <t>       wait <t> seconds between port hits
  -f, --tcpflags        customize TCP flags
  -h, --help            this help
```

## Donations
If you find this utility helpful and would like to support further development, consider making a [donation](https://github.com/m4cr0m4l).

Thank you for your contribution!
