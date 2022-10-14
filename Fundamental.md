## OP
- Operating System manages the computer`s memory, process, sofware and hardware. 
- Most of time, there are several different computer programs running at the same time and they all need to access computer`s  central processing unit(CPU),memory and storage. The OS coodinates all of this to make sure each programs gets what it needs.
- Three types: Microsoft Windows, macOC and Linux.
- Modern OS use a graphical user interface or GUI(let mouse to click icons, buttons and menus).
- Everything displayed on the screen using a combination of graphics and text.
- Linux: open-source OS, free and there are many different distributions/versions.
- Closed source sofware = proprietary sofware: the public is not given access to the source code, stable, focused product, often costs money.
- Open source sofware:publicly available to anyone who wants it, usually free ,public collaboration may fix bugs, add features and improve performance with a relatively short amout of time. It may not be user friendly as closed source software.
## Internet and Web
- Two computers communicate by cable or Wi-Fi and bluetooth. But if computers connect each other directly, it needs los of cables. 
- Computers send messages to a router first.This router  makes sure that a message sent from a given computer arrives at the right destination computer. Once we add a router to the system, our network of 10 computers only requires 10 cables: a single plug for each computer and a router with 10 plugs.
- By connecting computers to routers, then routers to routers, we are able to scale infinitely.
- To connect our network to the telephone infrastructure, we need a special piece of equipment called a modem. This modem turns the information from our network into information manageable by the telephone infrastructure and vice versa.
- An ISP is a company that manages some special routers that are all linked together and can also access other ISPs' routers. So the message from our network is carried through the network of ISP networks to the destination network. The Internet consists of this whole infrastructure of networks.
- If you want to send a message to a computer, you have to specify which one(IP).t's an address made of a series of four numbers separated by dots, for example: 192.168.2.10.
- We human beings have a hard time remembering that sort of address. We can alias an IP address with a human-readable name called a domain name( google.com is the domain name used on top of the IP address 142.250.190.78. )
- Internet is a technical infrastructure which allows billions of computers to be connected all together. Among those computers, some computers (called Web servers) can send messages intelligible to web browsers. The Internet is an infrastructure, whereas the Web is a service built on top of the infrastructure.
- web page: A document which can be displayed in a web browser such as Firefox. These are also often called just "pages."
- website: A collection of web pages which are grouped together and usually connected together in various ways. Often called a "web site" or a "site."
- web server: A computer that hosts a website on the Internet.
- search engine: A web service that helps you find other web pages, such as Google, Bing, Yahoo, or DuckDuckGo. Search engines are normally accessed through a web browser.
- How the web works: 
  - Computers connected to the internet are called clients and servers. Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.
  - TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. the shop, and buy your goods.
  - DNS: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place.
  - HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other.
  - Component files: A website is made up of many different files. These files come in two main types:
    - Code files: Websites are built primarily from HTML, CSS, and JavaScript.
    - Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.
- Process: When you type a web address into your browser :
  - The browser goes to the DNS server, and finds the real address of the server that the website lives on.
  - The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client across your internet connection using TCP/IP.
  - If the server approves the client's request, the server sends the client a "200 OK" message and starts sending the website's files to the browser as a series of small chunks called data packets.
  - The browser assembles the small chunks into a complete web page and displays it to you.
- Order in which component files are parsed :
  - The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
  - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
## Git
- Git is a technology used in the command line while GitHub is a website you can visit.


