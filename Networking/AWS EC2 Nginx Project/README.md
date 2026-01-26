# NGINX Website on AWS EC2: nginx.ahmednawaz.co.uk

This project documents setting up a static website on an AWS EC2 instance running NGINX.  
The website is accessible via a custom domain configured using Amazon Route 53.


## Prerequisites

- AWS account (free tier used to avoid EC2 charges)
- Custom domain purchased via Amazon Route 53


## Project Overview

This project demonstrates practical networking and cloud concepts, including:

- DNS resolution
- IP addressing
- Security group (firewall) configuration
- HTTP web serving
- Customising NGINX landing page

## Steps

1. Purchased a custom domain using Route 53  
2. Launched an EC2 instance running Amazon Linux  
3. Installed and configured NGINX  
4. Opened HTTP (port 80) access via security groups  
5. Created Route 53 A records pointing the domain to the EC2 instance  
6. Verified the website was accessible via the custom domain
7. Customised NGINX landing page  


## Result

The NGINX default page was replaced with a custom landing page, successfully served over HTTP via the domain

nginx.ahmednawaz.co.uk
