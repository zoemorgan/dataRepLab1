2: cURL is a computer software project providing a library and command-line tool for transferring data using various protocols

3:

HTTP Request:
GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*

HTTP Response:
 HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Mon, 16 Sep 2019 09:28:23 GMT

4: file created http-easy.html
moved permantently, url redirects

5: file created duckduckgo.html
moved permanently, url redirects

duckduckgo.txt contents:
<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx</center>
</body>
</html>

request/response:
GET / HTTP/1.1
> Host: duckduckgo.com
> User-Agent: curl/7.64.0
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Server: nginx
< Date: Mon, 16 Sep 2019 10:08:50 GMT
< Content-Type: text/html
< Content-Length: 162
< Connection: keep-alive
< Location: https://duckduckgo.com/
< X-Frame-Options: SAMEORIGIN
< Content-Security-Policy: default-src https: blob: data: 'unsafe-inline' 'unsafe-eval'; frame-ancestors 'self'
< X-XSS-Protection: 1;mode=block
< X-Content-Type-Options: nosniff
< Referrer-Policy: origin
< Expect-CT: max-age=0
< Expires: Tue, 15 Sep 2020 10:08:50 GMT
< Cache-Control: max-age=31536000

6: file created science.txt

7: file created gmit.json , added spacing

8: 50 requests

