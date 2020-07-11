
# Upcoming Google Chrome will not show parts of URLs

The latest google chrome developer edition browser canary has an experimental feature to hide all path levels from the URL except the domain name

so In future of the chrome browser, will hide the webpage path level of URL suffix from the Address bar

In the past year, they already rolled out similar features like hiding the prefixes such as ‘HTTP/HTTPS’ and ‘www.’ from the address bar

At the time Google has added the above feature into their canary version of chrome as an experimental option

When its has been enabled, Chrome will only show the domain name of the website and not the full page URL path. Here in the example, the URL with a path like`https://www.reddit.com/r/chrome/guide-for-analytics/` will simply show as `reddit.com/`

## Why?

Google believes this change will make the users, to **easily distinguish the phishing webpages** from the real one

> Before we jumping into the news section we will clear some ground concepts.

## what is mean by URL Path

The URL abbreviated by the *Uniform Resource Locator*. it's used to identify the resource on the server. The resource can be anything like HTML document, image, video file, or any file from the internet.

A URL is composed of different parts, some of them are important and others are optional

```
<https://www.example.com/path/to/myfile.html>
```

```https://``` ⇒ HTTPS is protocol abbreviated by *HyperText Transfer Protocol Secure*, it's most commonly used on the internet for data transfer between the client and server. It runs on top of TCP(*Transmission Control Protocol*) stack

At the ending `S` indicates a secure connection, It means the connection between the server and client has been encrypted by public/private key cryptography, it makes no one can eavesdrop or alter the ongoing connection

the ```www.example.com```is the domain name of the server, Alternatively, it is possible to directly use an IP address of that server, but it is less convenient and hard to remember, here the `www` is a subdomain

`/path/to/myfile.html` is the path, shows the location of that file named "myfile" from the server

these type of addressing is called as **location-based addressing.**

## What is a Phishing attack?

A phishing attack is a type of social engineering attempt to aim to steal personal information

they often send a webpage that looks exactly like your real banking website's login page. in the worst-case scenario if you mistakenly give your real bank login information on that fake website the outcomes will be disastrous.

Generally, you can't find any visual design difference from the real one, because anyone can design a webpage by their basic web development knowledge.

But there is not possible to spoof the actual domain name of the website. it proves you are on the real website.
But sometimes the spammers make the URL looks like a legitimate one by adding multiple subdomains in front of the actual domain name to trick you.

That showing a full URL may detract from the most important part of the URL – the domain name – which is crucial to know how secure and authentic the site is.

For example, the attacker purchases a domain named ```[evilsite.com]```, then they adding subdomains by configuring the DNS records. here in an example like ```twitter.com.evilsite.com```

here both ```twitter``` and ```com``` both are subdomains, the actual domain was still ```evilsite.com```

but sometimes the people in hurry failed to notice these minor changes, it will become a major mistake in their day.

## Use of that new feature:

If that new feature has been implemented in all the browsers, whatever the attackers try to modify their evil site with their multiple subdomain pattern, still the browser shows only the actual domain name of the site

so it makes it easy to identify the malicious websites even by the general user

## You can still see a full URL if you want.

if you want to share that URL or want to view the full URL path, its still possible to do. by clicking the address bar with the mouse

and also you have an option to opt-out from the feature to always view the full URL in default by choosing from the settings menu

Thanks for reading ...