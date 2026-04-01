# aws-static-website-project
Deployed a static website using AWS S3 and CloudFront

# AWS Static Website Hosting Project 🚀

## Project Overview
This project demonstrates how to deploy a scalable and cost-efficient static website using AWS cloud services.

## Business Scenario
A small business needs a fast, reliable, and low-cost website solution that can be accessed globally without managing servers.

## Solution
I built a serverless website using Amazon S3 for storage and Amazon CloudFront as a content delivery network (CDN) to improve performance and availability.

## Architecture
- Amazon S3 (static website hosting)
- Amazon CloudFront (global content delivery)

## Services Used
- Amazon S3
- Amazon CloudFront

## Implementation Steps
1. Created an S3 bucket and uploaded a static HTML file
2. Enabled static website hosting
3. Configured bucket policy for public access
4. Created a CloudFront distribution
5. Configured HTTPS and global delivery via CDN

## Key Learnings
- How object storage can replace traditional web servers
- How CDNs improve latency and performance
- How cloud solutions reduce infrastructure costs

## Business Impact
This solution eliminates the need for server management, reduces infrastructure costs, and delivers fast content globally.

## Future Improvements
- Add custom domain using Route 53
- Implement SSL certificate customization
- Add CI/CD pipeline for automated deployments
