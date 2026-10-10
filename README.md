# My Portfolio on AWS (S3 + CloudFront)

My personal portfolio page (plain HTML and CSS), hosted on AWS. The files are stored in Amazon S3 and delivered over HTTPS through the Amazon CloudFront CDN.

Live demo: https://d1vvvcka01k0i9.cloudfront.net

## How it is hosted
Browser -> CloudFront (CDN, HTTPS) -> S3 bucket (website files)

## Files
- index.html: the page content
- style.css: the styling

## What I learned
- What S3 buckets and objects are, and how to upload static files
- What a CDN is and how CloudFront caches content close to visitors
- How HTTPS and cache invalidation work when I change a file
- Why I keep account details and access keys out of the repository

## Notes
The live link works only while the AWS resources exist. I delete them when I finish practising to avoid leaving things running.

## Author
Muhammad Suleman
- GitHub: https://github.com/muhammadsuleman23
- LinkedIn: https://www.linkedin.com/in/muhammad-suleman-rajpoot
