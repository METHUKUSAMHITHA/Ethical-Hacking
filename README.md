# Ethical-Hacking

Task 1: To solve any 5 XSS labs

Domain : Web Security Academy
Solving 5 XSS LABS :
1) Reflected XSS into HTML context with nothing encoded
2) Stored XSS into HTML context with nothing encoded
3) DOM XSS in document.write sink using source location.search
4) DOM XSS in innerHTML sink using source location.search
5) DOM XSS in jQuery anchor href attribute sink using location.search source

Task 2: Finding Vulnerabilities and loophole using Automatic Vulnerability Scanner on website

Domain: zero.websecurity.com
Site Name: Zero Bank’s Website
Impact: An attacker can easily obtain session details and change the website's appearance, as well as change the data going from the user to the server.
Solution:
●Filter input on arrival. At the point where user input is received, filter as strictly as possible based on what is expected or valid input.
●Encode data on output. At the point where user-controllable data is output in HTTP responses, encode the output to prevent it from being interpreted as active content. Depending on the output context, this might require applying combinations of HTML, URL, JavaScript, and CSS encoding
Worked on analyzing of Netspaker

Task 3: Finding Vulnerabilities on website

Domain: BurpSuite
STEPS TO FIND THE VULNERABILITY
1) Open Burp Suite Check Whether The Intercept Is On.
2) Open Firefox And Search For Vulnweb.
3) Click On Http://testasp.vulnweb.com The Given Interface Will Be Opened 
4) Click On Search Bar And Click The Foxyproxy On
5) Try To Enter One Of The Payloads So The Request Will Be Sent To Burpsuite
6) After The Request Comes Send It To Intruder And Forward The Request
7) Add The Payload Position Only For The Required Place
8) Add The Xss Payloads ,which Can Be Downloaded From Www.github.com
9) Start The Attack And Check Whether There Is Sudden Change In Length And Status.
10) Copy The Url To Show The Response For The Paylod That Has Been Accepted 
11) Copy The Url And Search It In Firefox 
12) The Required Interface Will Be In This Form.
 
