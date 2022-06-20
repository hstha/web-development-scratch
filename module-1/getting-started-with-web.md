# Getting Started With Web

## What is web and how does it work?

- A web is a collection of web pages that are linked together.
- It consists of client and server.

### Client and Server

- Client is a computer that request resources to the server. It is mainly browser.
- Server is a computer that store resources. When client wants to access a resource, server sends a copy of resource to the client for either displaying or downloading purpose.

### Communication between client and server:

- There are various components involved in the process of communication between client and server. These components are:

  - Internet Connection
    - Allows you to send and receive data over the internet.
  - TCP/IP
    - The communication protocols that defines how data should travel across the internet.
  - DNS
    - Domain Name System is an address book for websites.
    - When we type a web address in our browser, browser looks into DNS to find the website's IP address before sending request to the server.
  - HTTP
    - Hypertext Transfer Protocol is a set of rules that defines how data should be transferred across the internet.
  - Files
    - A website is made up of many different files.
    - These files are of two types:
      - Code Files:
        - A languages that are used to build websites. These files are mainly HTML, CSS and JavaScript.
      - Assets Files:
        - This is a collective name for all the other stuff that makes up a website, such as images, music, video, word documents and PDFs.

- What is difference between Website Address and IP Address?

  - Website Address: It is a virtual address of the website. It is used to remember the name of the website than numbers. Eg: www.google.com
  - IP Address: It is a unique address that identifies a device on the internet or a local network. Eg: 192.168.1.1

- How communication happens:
  - When we type website address into a browser, browser looks into DNS to find the website's IP address.
  - Then browser sends an HTTP request message to the server, asking it to send a copy of the website to the client.
  - All the message and data sent between the client and server, is sent across internet using TCP/IP.
  - If the server approves the client's request, the server sends the client a "200" message. Then starts sending files to the browser as a series of small chunks called data packets.
  - If the server rejects the client's request, the server sends the client a "400" message.
  - If the browser receives a "200" message then it assembles those chunks of data into a complete web page and displays it to you.
  - If the browser receives a "400" message then it displays an error message to you.

### Order in which component files are parsed

- N/A

### Why packets are sent in small chunks?

- When data is sent across the web, it is sent in thousands of small chunks. There are multiple reasons why data is sent in small packets. They are sometimes dropped or corrupted, and it's easier to replace small chunks when this happens.
- Additionally, the packets can be routed along different paths, making the exchange faster and allowing many different users to download the same website at the same time.

## What is HTML and how does it work?

- HTML is a descriptive language that allows us to tell a web browser how to handle text content.
- HTML is an acronym for HyperText Markup Language.
- HTML provides a system to annotate some plain text with tags.
- Those tags add semantic value to any text that will be used by browser to understand how to handle that text.
- HTMl follow rules defined by the HTML Specification which is maintain by the World Wide Web Consortium a.k.a W3C.
- That specification defines all the expected behaviors pf am HTML documents, which includes more than a hundred elements with all their associated nesting constrains.

## What is css and how does it style web pages?

- CSS is a descriptive language that defines the look and feel of each HTML element.
- CSS is an acronym for Cascading Style Sheets.
- CSS is like makeup for HTML.
- There is always the default style sheet for each tag in every browser has.
- Browsers allow their users to create and apply their own style sheets to any HTML document of their choice.

## What is JavaScript and how does it work?

- It is a prototype based programming language that is used to add interactivity to HTML documents.
- It is used to modify the behavior of HTML elements, make network requests, and perform other tasks that are not possible with HTML.
- It is made of ECMAScript, which is a standard for the specification of JavaScript.
- It has access to asynchronous and synchronous APIs.
