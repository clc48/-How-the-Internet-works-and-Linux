# -How-the-Internet-works-and-Linux
ISS17 assignment

We use it daily but do we really comprehend how it works? Unfortunately most of us don't, so here is a simple tutorial explaining how the internet works!
<img src="https://www.howtogeek.com/wp-content/uploads/2018/02/img_5a78dece9a202.jpg" alt="no picture found">

#  IP ADDRESS
WHAT IS AN IP ADDRESS ?

The "IP" part of IP address stands for "Internet Protocol." The "address" part refers to a unique number that gets linked to all online activity you do...
somewhat like a return address on a letter you'd send out. (All this happens in milliseconds.)
Because the Internet is a global network of computers each computer connected to the Internet must have a unique address. Internet addresses are in the form
nnn.nnn.nnn.nnn where nnn must be a number from 0 - 255.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Ipv4_address.svg/300px-Ipv4_address.svg.png">


If you still have questions here is a a link to a short but precise clip on what an Ip address is:
https://youtu.be/7_-qWlvQQtY


# DNS
Now that we have a concept of what an Ip address is we must understand what is a DNS:
First of all, DNS is an acronym that stands for Domain Name System. DNS is an Internet service that translates domain names/hostnames to IP addresses (forward DNS) and IP addresses to
their associated domain names/hostnames (Reverse DNS) with the help of a DNS server.

**THINK OF A DNS AS A PHONE BOOK, THE IP ADRESS IS THE PHONE NUMBER AND THE DNS PROVIDES YOU WITH THE PERSON'S NAME, WHICH IS OF COURSE EASIER FOR US TO REMEMBER AND THEREFORE MORE USER FRIENDLY**
<img src="https://previews.123rf.com/images/jemastock/jemastock1608/jemastock160812083/61748477-flat-design-cute-lightbulb-icon-vector-illustration.jpg">

How DNS Works in 6 Easy Steps:

1.The user logs onto their Internet Service Provider (ISP) to use the Internet. 

2.The user opens up a web browser (Firefox, Chrome, Internet Explorer(if you are are living in prehistoric times), Safari, etc.) 
and types a URL into the address bar. For example, perhaps the user types in https://www.github.com/.

3.The computer then asks for the ISP’s DNS servers for the specific IP address for www.github.com

4.Once the DNS server that holds this specific IP address for www.github.com is found, the DNS server responds with the appropriate IP address and the user’s computer then gives this address to the user’s browser.

5.The browser opens a connection to the server using the IP address provided and retrieves the page from the site requested, in this case for www.github.com

6.The browser displays the requested page on the computer screen.


#DOMAIN NAMES AND TLD'S 
A domain name is simply the name assigned to an IP address. As we mentioned before, if the IP address is the phone number in a phonebook, the DNS is the phonebook itself therefore the tool we use to find it, and the Domain name would be the equivalent to the 
contact's name.
 
A domain name takes the form of two main elements. For example, the domain name Github.com consists of the website’s name (Github) and the domain name extension (.com). 
When a company (or a person) purchases a domain name, they’re able to specify which server that the domain name points to.
Every domain name has a suffix that indicates which top level domain (TLD) it belongs to.
Top-level domains serve as an instant way to understand what a website is about or where it's based.

For example, seeing a .edu address, like in www.njit.edu will immediately inform you that the material on the website is centered around education. 

There's also a side effect TLDs, which is that because there are several options, multiple websites can use the same name but be totally different sites or companies. Apart from the last bit where the TLD sits, the URLs might be identical.

For example, github.com is a website but github.org is another with the same name but different TLD, so they're actually completely different websites. 

It's for this reason that some companies will register multiple TLDs so that anyone going to the other, non-primary URLs, will still land on the company's website. For example, google.com is how you reach Google's website, but you can also get there through google.net. However, google.org is a totally different website.

There are only a limited number of such domains. Here are a few for example:

gov - Government agencies

edu - Educational institutions

org - Organizations (nonprofit)

com - commercial business

net - Network organizations

ca- Canada

Websites like godaddy.com allow the public to purchase Domain names as long as they are available. So if you are thinking of starting your own business or a blog you could have your own Domain name! (This is not an ad for godaddy i swear)
<img src="https://1.bp.blogspot.com/-_zldwgR2ebo/VL9vljXkevI/AAAAAAAAhhM/nJ-6C3RpEQU/s728/godaddy-domain-hosting-hack.png">


#How to read a web address ie: https://www.youtube.com
1."**protocol://**" - This defines what Internet protocol is required to reach the online resource.
(In our example **https://**)

2."**computer.domain.name**" - The domain name of the server where the information is located (can also be the server's IP number)
(In our example **www.youtube**)

3." **TLD**" - The very last section of an internet domain name, located after the last dot, to help form a fully qualified domain name.
(In our example **.com**)

#HTTP & HTTPS

In short, both of these are protocols using which the information of a particular website is exchanged between Web Server and Web Browser. But what’s difference between these two?

In the beginning, network administrators had to figure out how to share the information they put out on the Internet.
They agreed on a procedure for exchanging information and called it HyperText Transfer Protocol (HTTP).
HTTP is a protocol using which hypertext is transferred over the Web. HTTP has different methods such as request method, GET (requests data from a specified resource)and POST (submits data to be processed to a specified resource). Due to its simplicity, http has been the most widely used protocol for data transfer over the Web but the data (i.e. hypertext) exchanged using http isn’t 
as secure as we would like it to be. In fact, hyper-text exchanged using http goes as plain text i.e. anyone between the browser and server can read it relatively easy if one intercepts this exchange of data.

This is when HTTPS comes in play, HTTPS adds a layer of security on the data in transit through a secure socket layer (SSL) or transport layer security (TLS) protocol connection. Basically, the computers agree on a "code" between them, 
and then they scramble the messages using that "code" so that no one in between can read them. 
This keeps your information safe from hackers.

<img src="https://seopressor.com/wp-content/uploads/2017/07/Difference-Between-HTTP-and-HTTPS.png">


Another syntactic difference between http and htpps is that http uses default port 80 while https uses default port 443. 

Previously we mentioned SSL which is another difference between HTTP AND HTTPS AS HTTPS requires SSL certificates. 
SSL (Secure Sockets Layer) is the standard security technology for establishing an encrypted link between a web server and a browser. This link ensures that all data passed between the web server and browsers remain private and integral. SSL is an industry standard and is used by millions of websites in the protection of their online transactions with their customers.
To be able to create an SSL connection a web server requires an SSL Certificate. When you choose to activate SSL on your web server you will be prompted to complete a number of questions about the identity of your website and your company.

Here is a link to a video on more about HTTP,HTTPS & SSL: 
https://youtu.be/hExRDVZHhig



#REST and Roy Fielding's dissertation
<img src="https://cdn-images-1.medium.com/max/1200/0*GN2n0rtrVwEN5XlM">

 In the simplest term, REST considered to be a set of principles that assign how HTTP and URLs Web standards are used. The main idea is that if you comply REST principles while developing your application you will have a system that uses the Web’s architecture to your benefit.
 
 Guiding Principles of REST
 
1. Client–server – By separating the user interface concerns from the data storage concerns, we improve the portability of the user interface across multiple platforms and improve scalability by simplifying the server components.

2. Stateless – Each request from client to server must contain all of the information necessary to understand the request, and cannot take advantage of any stored context on the server. Session state is therefore kept entirely on the client.

3. Cacheable – Cache constraints require that the data within a response to a request be implicitly or explicitly labeled as cacheable or non-cacheable. If a response is cacheable, then a client cache is given the right to reuse that response data for later, equivalent requests.

4. Uniform interface – By applying the software engineering principle of generality to the component interface, the overall system architecture is simplified and the visibility of interactions is improved. In order to obtain a uniform interface, multiple architectural constraints are needed to guide the behavior of components. REST is defined by four interface constraints: identification of resources; manipulation of resources through representations; self-descriptive messages; and, hypermedia as the engine of application state.

5. Layered system – The layered system style allows an architecture to be composed of hierarchical layers by constraining component behavior such that each component cannot “see” beyond the immediate layer with which they are interacting.

6. Code on demand (optional) – REST allows client functionality to be extended by downloading and executing code in the form of applets or scripts. This simplifies clients by reducing the number of features required to be pre-implemented.