NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.




Why use NGINX?

NGINX provides various services such as reverse proxy, load balancer, and rate limit network services. Reverse proxying is useful if we have multiple web services listening on various ports and we need a single public endpoint to reroute requests internally. This would allow us to host multiple domain names on port 80 while using a combination of different NodeJs, Go and java to power separate web services behind the scenes.

Nginx can handle the logging, blacklisting, load balancing and serving static files while the web services focus on what they need to do.

The configuration of Nginx is easier than Apache httpd. Nginx was designed for high concurrency and it is very fast.



Features of NGINX

Some features of Nginx are as follows:

    Reverse proxy with caching
    IPV6
    Load Balancing
    Web Sockets
    Handling of static files, index files, and auto-indexing
    FastCGI support with caching
    URL rewriting and redirection
