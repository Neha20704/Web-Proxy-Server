# Web Proxy Server  
**Mini Project on Computer Networks: Web Proxy Server**  

---

## **Overview**  
This project implements a web proxy server in Python using socket programming. It enables the creation of a basic proxy server capable of handling HTTP requests and responses.  

---

## **Key Features**  
- Facilitates communication between clients and servers by acting as an intermediary.  
- Supports basic HTTP GET requests.  
- Allows easy configuration of the proxy server's host and port.  

---

## **Requirements**  
- Python 3.x  
- Active internet connection (to proxy external websites).  

---

## **How to Use**  
1. Clone this repository to your local machine.  
2. Open a terminal and navigate to the project directory:  
   ```bash
   cd python-proxy-server
   ```
3. Adjust the `proxy_host` and `proxy_port` variables in the `main()` function of `proxy_server.py` as needed.  
4. Start the proxy server by running the script:  
   ```bash
   python proxy_server.py
   ```
5. When prompted, enter the listening port number and confirm.  
6. Once running, you can send HTTP requests through the proxy server.  

---

## **Configuration Options**  
- To set a different listening port, update the `listen_port` variable in the `main()` function of `proxy_server.py`.  
- To adjust the maximum allowed connections, modify the `max_conn` variable in the script.  
- To customize the buffer size for data transmission, update the `buffer_size` variable.  

---

## **Contributing**  
Contributions are highly encouraged! Feel free to submit pull requests for bug fixes or feature enhancements, or open issues for discussions.  

--- 
