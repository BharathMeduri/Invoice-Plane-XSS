# Invoice-Plane-XSS -- CVE-2018-12255
Stored XSS in invoiceplane demo website v1.5.10

Stored XSS in invoice plane application

in the invoice plane in below link 
https://demo.invoiceplane.com/index.php/quotes/view/22

and functionality "Quote PDF Password(Optional)" is vulnerable to XSS like Stored , Reflected , Cookie , possible for more

 

Payloads : "><script>alert("Hello Stored XSS")</script>
"><script>alert("document.cookie")</script>

and follow the below images

to get confirm

impact: An attacker can use this vulnerability to inject malicious code into the application, which will execute in
the browser of any user who is viewing the relevant application content. The attacker code can 
perform wide variety of actions such as stealing the target user cookies or performing actions on their behalf 
and also can capture the keystrokes of the user.

