# post-mortems
Here I collect post-mortem stories of hacks &amp; outages.

[Capital One](https://krebsonsecurity.com/tag/capital-one-breach/) - [WAF](https://aws.amazon.com/waf/?nc1=h_ls) was misconfigured and had too many permissions, which allowed the hacker to [forge](https://www.hackerone.com/blog-How-To-Server-Side-Request-Forgery-SSRF) a request to a metadata service and retrieve elevated credentials.\
🗒️ [Details](https://ejj.io/blog/capital-one), [More details](https://ejj.io/blog/fixing-capital-one).\
🏷️ configuration, security, AWS, IAM, WAF
