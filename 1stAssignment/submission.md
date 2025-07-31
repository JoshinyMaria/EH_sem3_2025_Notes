# Simple Python HTTP Server

## Methodology:
- Use Python's built in module [http.server] to create a HTTP server accessible from the CLI broadcast over the local network.
- Involves downloading python, setting up a directory for broadcast, navigating to said directory and then broadcasting on a specified port using the module
- Test by opening the broadcasted port on the same machine or another one connected on the same local network.

## Code
- Usage of simple terminal instruction
- For the purposes of this project I have utilised the terminal from VSCode, however this can be performed on any terminal (Powershell, etc.)
- Commands
```
cd D:\joshiny\python\Media\
python3 -m http.server 8080
```

## Screenshots
### Terminal
<img width="728" height="106" alt="image" src="https://github.com/user-attachments/assets/9ccc2015-78bb-4420-8b5f-70f968426b33" />

### Served Directory at port 8080 using localhost as ip 
<img width="1011" height="490" alt="image" src="https://github.com/user-attachments/assets/9308e70f-dc02-4636-ab4a-e7e4974c75fe" />

### Accessing served directory using local IPv4 adress
![Image 2025-07-31 at 23 45 54_3faac56f](https://github.com/user-attachments/assets/c6f984de-2fd3-459c-998f-bf41655e970a)

## Findings
- This is a simple simulation of broadcasting a directory over the network for various use cases
- The module was easy to use and implement. It was straightforward and required little to no backend support
- The broadcast will only work within the local network (unless the port is forwarded)

## Conclusion
- While this is a simple simulation, the principle finds large scale uses on a daily basis.
- File sharing on the internet through websites, media sharing through apps and at home, or connecting mutliple machines at a firm.
- The module execution demonstrates this in a simple fashion making it easy to understand.


