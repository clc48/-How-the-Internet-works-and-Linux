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

