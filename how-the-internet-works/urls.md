---
layout: page
title: Internet Addresses
permalink: /how-the-internet-works/urls
category: how-the-internet-works
order: 22
---

# URLs: Addresses for the Internet

On the page [How the Internet works](/how-the-internet-works), I wrote:

> The Internet is millions of computers, all connected together.

And on the page [What is a website?](/how-the-internet-works/websites), I wrote:

> When you view a simple website, such as this one, you're really reading a file stored on a computer.

So how can you find the specific file you're looking for on just one of those millions of computers? Fortunately, every file on the Internet has an address. These addresses are called **Uniform Resource Locators**, or **URL**s. 

A physical address subdivides the physical worls into a series of steps -- Country, State, City, Street, and House Number -- to make it easier for people to find it. Similarly, a URL subdivides the internet into a series of steps to make it easy for you to find a specific file on a specific computer.

<figure class="image">
  <img src="/images/url-structure.jpg" alt="Structure of URLs">
  <figcaption>Structure of URLs, courtesy of <a href='https://commons.wikimedia.org/wiki/File:URL_structure.jpg' target='_blank'>Wikipedia</a></figcaption>
</figure>

* The main organizing unit of internet addresses is the **domain**. Examples of a domain are _[google.com](https://google.com){:target="_blank"}_, _[wikipedia.org](https://wikipedia.org){:target="_blank"}_, _[whitehouse.gov](https://whitehouse.gov){:target="_blank"}_, etc. A single domain is usually controlled by a single person or company, and it may have many pages contained within it.
  * Each domain name also includes a **top-level domain (TLD)**, such as _.com_, _.org_, _.gov_, and more.
* Some domains may be organized into **subdomains**. A subdomain appears to the left of the domain, and is typically used to split up a domain. For example, [Wikipedia](https://en.wikipedia.org/wiki/Main_Page){:target="_blank"} has English site at _[en.wikipedia.org](https://en.wikipedia.org){:target="_blank"}_ and a French site at _[fr.wikipedia.org](https://fr.wikipedia.org/){:target="_blank"}_.
* Within a domain or a subdomain, there could be thousands of individual web pages or files, with each file given its own unique **path**. After the _domain_ and _TLD_, there will be a slash (/). Anything after the slash is the **path** of the web page.
* Occasionally, the path may include a hash mark (#). This is called an **anchor**; anchors provide a way of naming not just a file, but specific parts within that file.

How does a paricular domain get matched to a particular set of computers and files? That's a complicated question that I won't cover in detail here. The short answer is that it's the responsibility of the **Domain Name System (DNS)**. If you want to learn about about DNS, see [this article](https://www.verisign.com/en_US/website-presence/online/how-dns-works/index.xhtml){:target="_blank"} from DNS provider [VeriSign](https://www.verisign.com/en_US/website-presence/online/how-dns-works/index.xhtml){:target="_blank"}.