** Deploy Static Website on AWS (S3 + CloudFront**

This project demonstrates deploying a static website using **Amazon S3**, configuring access with **IAM Policies**, and distributing content globally via **Amazon CloudFront**. The website contains only static assets (HTML/CSS/JS) and does not require server-side processing.

## Live Demo (CloudFront URL)

**Public Website:**  
https://d2c7k5ls9gey4e.cloudfront.net/

 🏗️ Architecture Overview

The deployment setup includes:

- **Amazon S3** — Hosts the static website files.
- **IAM Bucket Policy** — Allows public read-only access to objects.
- **Amazon CloudFront** — CDN service to accelerate content delivery globally.
- **Static Website Endpoint** — Configured under S3 Bucket Properties.


## 📦 AWS Resources Used

| Service     | Purpose |
|-------------|---------|
| S3          | Website hosting & file storage |
| IAM Policy  | Public access control |
| CloudFront  | CDN distribution & caching |




