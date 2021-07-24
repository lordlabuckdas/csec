# websec

## books

* [tangled web]()

## gh repos

* [webapp hacking mindmap](https://github.com/nmmcon/MindMaps)
* [ssrf guide](https://github.com/MustafaSky/Guide-to-SSRF)

## blogs

* [daffainfo's bugbounty notes](https://github.com/daffainfo/AllAboutBugBounty)
* [subdomain enumeration](https://sidxparab.gitbook.io/subdomain-enumeration-guide/introduction/whats-the-need)

## labs

* [mutllidae](https://github.com/webpwnized/mutillidae)
* [dvwa](https://dvwa.co.uk/)
	* low diff
	* mid diff
	* high diff
* [portswigger academy](https://portswigger.net/web-security)
* [Kontra's OWASP Top 10 for Web](https://application.security/free/owasp-top-10)

## courses

* [stanford cs253](https://web.stanford.edu/class/cs253/)
* [mit computer systems security](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/)
* [mit network and computer security](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-857-network-and-computer-security-spring-2014/)

## gh repos

* [google vrp writeups](https://github.com/xdavidhu/awesome-google-vrp-writeups)

## methodology

Penetrating a web application? Here is the list of test cases you can try on any input field.

- Fuzz all request parameters (if got user, add headers to fuzzer)
- Identify all reflected data
- Reflected XSS
- HTTP header injection in GET & POST (X Forwarded Host)
- RCE via Referer Header
- SQL injection via User-Agent Header
- Arbitrary redirection
- Stored attacks
- OS command injection
- Path traversal, LFI, and RFI
- Script injection
- File inclusion
- SMTP injection
- Native software flaws (buffer overflow, integer bugs, format strings)
- SOAP injection
- LDAP injection
- SSI Injection
- XPath injection
- XXE in any request, change content-type to text/xml
- Stored XSS
- SQL injection with ' and '--+-
- NoSQL injection
- HTTP Request Smuggling
- Open redirect
- Code Injection (`<h1>Hey</h1>` on stored param)
- SSRF in previously discovered open ports
- xmlrpc.php DOS and user enumeration
- HTTP dangerous methods OPTIONS PUT DELETE
- Try to discover hidden parameters (arjun or parameth)

## publications

* research_papers dir
