[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

# Contributing

Thank you for your interest in contributing to the NGINX best practices!  
If you have any questions that aren't covered by this document, please [open an issue][issue] or start a [Q&A discussion][discussion] in GitHub.

[issue]:https://github.com/nginx/best-practices/issues/new?labels=question
[discussion]:https://github.com/nginx/best-practices/discussions/new?category=q-a

## Getting Started

Write the documentation in [Markdown][md] and build the NGINX documentation site using [Hugo](https://gohugo.io/).
NGINX documentation uses the [CommonMark][cmnmark] Markdown flavor.

[md]: https://www.markdownguide.org/
[cmnmark]: https://commonmark.org/

## Adding a new document

1. Clone this repo.
1. Check out a new feature branch from main.
1. Make a copy of the [template](template.md) in the [content](/content/) directory.
1. Give your new file a name that represents the content.
1. Following the guidance in the template, build out your new best practice doc.
1. Make [atomic commits][atomic commits] as you work.
1. Open a [pull request][pr] when your work is ready for review.

[atomic commits]: https://www.aleksandrhovhannisyan.com/blog/atomic-git-commits/
[pr]: https://github.com/nginx/best-practices/pulls

## Style and Tone

Keep the following rules in mind when writing for and about NGINX:

1. Always write "NGINX" in all caps, except when referring to a command or process.

    For example:  
    "NGINX is the most popular web server on Earth."  
    "Use the `nginx -s reload` command to reload your configuration."

1. Use active voice. Tools like [Grammarly] and [Hemingway] can help you refine your content.
1. Don't assume the reader is a subject-matter expert. Give enough background information that a new NGINX user can understand and follow your instructions.

[Grammarly]:https://www.grammarly.com/where-grammarly-works
[Hemingway]:https://hemingwayapp.com/

## Target Personae

NGINX is many things to many people. Those people perform various job roles across many different industries. Some of these roles may intersect.

When writing a best practice doc, you should approach the subject with one or two of the personae described in this section in mind. This helps ensure that the use case isn't too broad to apply to any individual user's real-world needs.

> :question: Looking for a persona that isn't listed here?  
> Add your suggestion and [open a pull request](https://github.com/nginx/best-practices/pulls).

### Application Developers

Application developers use NGINX to enhance the performance and scalability of their applications, including serving static assets, caching, and managing requests to back end application components.  
The applicable NGINX products are:

- NGINX Open Source
- NGINX Unit
- NGINX Plus
- NGINX Ingress Controller
- NGINX Management Suite Instance Manager
- NGINX Management Suite API Connectivity Manager
- NGINX Management Suite App Delivery Manager

### DevOps and PlatformOps Engineers

DevOps and PlatformOps engineers use NGINX to route incoming traffic to the appropriate back end services; distribute load across servers; and handle SSL termination.  
The applicable NGINX products are:

- NGINX Open Source
- NGINX Plus
- NGINX Ingress Controller

### Network Engineers

Network engineers use NGINX to manage network traffic and distribute it across various backend servers.  
The applicable NGINX products are:

- NGINX Open Source
- NGINX Plus
- NGINX Ingress Controller
- NGINX Management Suite Instance Manager
- NGINX Management Suite API Connectivity Manager
- NGINX Management Suite App Delivery Manager

### Security Professionals

Security Professionals use NGINX as a web application firewall (WAF), filtering out malicious traffic, and for denial of service (DoS) protection. The applicable NGINX products are:

- NGINX App Protect WAF
- NGINX App Protect DoS
- NGINX Management Suite Instance Manager
- NGINX Management Suite Security Monitoring

### System Administrators

System administrators use NGINX to optimize resource utilization, enhance security, and balance server loads.  
The applicable NGINX products are:

- NGINX Open Source
- NGINX Plus
- NGINX Ingress Controller
- NGINX App Protect WAF
- NGINX App Protect DoS
- NGINX Management Suite Instance Manager
- NGINX Management Suite Security Monitoring

### Web Administrators

Web administrators use NGINX to manage web servers, configure virtual hosts, and optimize server performance.  
The applicable NGINX products are:

- NGINX Open Source
- NGINX Unit
- NGINX Plus
- NGINX Management Suite Instance Manager
