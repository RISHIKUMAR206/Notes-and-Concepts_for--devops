&nbsp;                                                             ***Understanding DNS, Subdomains, Host Addresses and DNS Records***



1\) DNS (Domain Name System)

➤ Overview:



DNS is a system that connects a domain name to its actual IP address.



➤ How it works:



You type a website name in your browser (like example.com).



Your system asks DNS for its IP address.



DNS finds the correct IP from the name server.



Your browser connects to that IP and loads the website.



➤ Why we use it:



Humans remember names easily, not numbers.



DNS converts names into machine-readable IP addresses.



➤ Benefits:



Easy access to websites.



Faster internet browsing.



You can change hosting without changing domain name.



2\) Subdomain

➤ Overview:



A subdomain is a part added before the main domain.



Example:

blog.example.com

Here "blog" is the subdomain.



➤ How it works:



Subdomain points to a specific folder, service, or server.



It works using DNS records just like the main domain.



➤ Why we use it:



To separate website sections.



To organize content properly.



➤ Benefits:



Better website structure.



Can run different services under one domain.



No need to buy a new domain.



3\) Host Address (IP Address)

➤ Overview:



Host address is the real numeric address of a server.



Example:

192.168.1.1



➤ How it works:



Every server has an IP address.



DNS connects domain name to this IP.



➤ Why we use it:



Computers communicate using IP addresses.



It identifies the exact server location.



➤ Benefits:



Accurate server connection.



Unique identity for every server.



4\) Name Servers (NS Records)

➤ Overview:



Name servers store and manage DNS records of your domain.



➤ How it works:



When someone searches your domain,



The request goes to name servers.



They provide correct DNS information.



➤ Why we use it:



To manage domain settings.



To control website and email routing.



➤ Benefits:



Full control over DNS.



Easy to update website or email settings.



5\) Mail (MX) Servers

➤ Overview:



MX record tells where emails for your domain should go.



➤ How it works:



When someone sends email to you@example.com

,



MX record directs it to your mail server.



➤ Why we use it:



To receive emails properly.



To connect domain with email service.



➤ Benefits:



Reliable email delivery.



Can use services like Google Workspace or Outlook.



6\) TXT Records

➤ Overview:



TXT record stores text information in DNS.



➤ How it works:



Services check TXT record for verification.



Email systems check it for security rules.



➤ Why we use it:



Domain verification.



Email security (SPF, DKIM, DMARC).



➤ Benefits:



Prevents email spam and spoofing.



Improves email trust and security.

