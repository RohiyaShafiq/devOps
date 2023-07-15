# What is and how to setup a________ :
## Reverse Proxy:
- An application that sits in front of back-end applications and forwards client (e.g. browser) requests to those applications.
- Help increase scalability, performance, resilience and security.
- Provides an additional level of abstraction and control to ensure the smooth flow of network traffic between clients and servers.
- Common Uses:
    - Load balancing
    - Web acceleration
    - Security and anonymity
- Benefits of reverse proxy servers include:
    - global server load balancing (GSLB).
    - caching content and web acceleration for improved performance.
    - more efficient and secure SSL encryption.
- Offered by many vendors such as VMware, F5 Networks, Citrix Systems, A10 Networks, Radware, and Public Cloud platforms such as Amazon Web Services and Microsoft Azure.
## Forward Proxy:
- often called proxy server, is an intermediary that sits between one or more user devices and the internet.
- A forward proxy server will first check to make sure a request is valid. If a request is not valid, or not allowed (blocked by the proxy), it will reject the request resulting in the client receiving an error or a redirect.
- If a request is valid, a forward proxy may check if the requested information is cached. If it is, the forward proxy serves the cached information. 
- Common Uses:
    - To block access to certain content.
    - To protect client identity online.
    - To provide restricted internet to organizations.
- Benefits of a Forward Proxy:
    - User Privacy
    - Policy Enforcement
    - Traffic Visibility
    - Shadow IT Detection
## Firewall:
- A network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.
- A barrier that sits between a private internal network and the public Internet.
- Main purpose is to allow non-threatening traffic in and to keep dangerous traffic out.
- Different types of firewall:
    - Proxy firewall
    - Stateful inspection firewall
    - Next-generation firewall (NGFW)
- Popular use cases involve managing the following:
    - Parental controls
    - Workplace web browsing restrictions
    - Nationally controlled intranet
## Caching Server:
- A dedicated network server or service acting as a server that saves webpages or other internet content locally.
- Reduce network traffic and speed up access to frequently requested content by caching that content.
- Content caching servers can be located at ISPs and Network Access Points (NAPs) for improving the performance and responsiveness of the Internet.
- Speeds up access to web information while reducing demand on bandwidth used by an enterprise. 
- Server cache is an umbrella term covering several different types of caching. This includes:
    - Content Delivery Network (CDN) caching
    - object caching
    - opcode caching
## Load Balancer:
- The practice of distributing computational workloads between two or more computers.
- On the Internet, load balancing is often employed to divide network traffic among several servers. 
- Load Balancer Uses:
    - Automatically detect server failures and redirect client traffic.
    - Allow for server maintenance without any impact.
    - Provide automated disaster recovery to backup sites.
- A load balancer performs the following functions:
    - Distributes client requests or network load efficiently across multiple servers.
    - Ensures high availability and reliability by sending requests only to servers that are online.
    - Provides the flexibility to add or subtract servers as demand dictates.
## Web Servers:
- A computer where the web content is stored. Basically web server is used to host the web sites but there exists other web servers also such as gaming, storage, FTP, email etc.
- Web servers can also limit the speed of response to different clients so as to prevent a single client from dominating resources that are better used to satisfy requests from a large number of clients.
- Web servers typically host websites that are accessible on the Internet, they can also be used to communicate between web clients and servers in local area networks such as a company’s intranet.
1. Nginx:
- It is an open-source, fast, lightweight and high-performance web server that can be used to serve static files.
- NGINX is commonly used as a reverse proxy and load balancer to manage incoming traffic and distribute it to slower upstream servers – anything from legacy database servers to microservices.
- The goal behind NGINX was to create the fastest web server around, and maintaining that excellence is still a central goal of the project.
- NGINX improves content and application delivery, improves security, and facilitates scalability and availability for the busiest websites on the internet.
2. Tomcat:
- Tomcat is web server software that focuses on Java applications.
- Using Internet connectivity, Tomcat renders and presents the data to the web application. This way, you can access data from the web server anywhere worldwide.
- It implements the Java specifications on the web server that works as the remote controller to the physical computer design to server the files.
- Advantages of Tomcat Server:
    - Flexible
    - Stability
    - Well Documented
    - Open Source Application
3. Apache:
- A free, open-source HTTP server, available on many operating systems, but mainly used on Linux distributions. 
- Apache performs many tasks:
    - It receives your request to access a web page.
    - It runs a few security checks on your HTTP request and takes you to the web page.
    - It may ask the server to run extra modules while generating the document to serve you.
    - It then serves you the document you requested.
- Advantages of Apache:
    - It is beginner-friendly and relatively easy to learn.
    - The software is generally reliable, and has frequent patches to improve its performance and reduce security vulnerabilities.
    - Apache works well with programming languages such as PHP and Python.
    - There is a large community of developers and support if you run into any issues.
4. IIS:
- This web server software was created by Microsoft and therefore supports all platforms that use Windows operating systems.
- The IIS accepts and responds to the client's computer requests and enables them to share and deliver information across the LAN (or Local Area Network) such as a corporate intranet and the WAN (or Wide Area Network) the internet.
- It hosts the application, websites, and other standard services needed by users and allows developers to make websites, applications and virtual directories to share with their users.
- Benefits of using IIS server:
    - Robust security
    - Application pools
    - Scalability and reliability
            

