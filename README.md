# AWS Static Website Hosting with S3 and Route 53

This project demonstrates how to build and deploy a fully serverless static website using Amazon Web Services (AWS). It uses **Amazon S3** for static file hosting and **Route 53** to configure a custom domain name. The project is version-controlled with Git and hosted on GitHub.

## 📌 Features

- ✅ Static site hosted on Amazon S3
- 🌐 Custom domain name setup using Route 53
- 🔒 (Optional) HTTPS enabled using CloudFront and ACM
- 📄 Public bucket policy and error handling with `error.html`
- 📁 GitHub repository for version control and documentation

## 🛠️ Technologies Used

- **Amazon S3** – for static website hosting  
- **Amazon Route 53** – for domain name registration and DNS routing  
- **Amazon CloudFront** (optional) – for CDN and HTTPS  
- **Git + GitHub** – for version control and project tracking

## 🚀 Deployment Steps

1. Create and configure an S3 bucket for static hosting
2. Upload `index.html` and `error.html`
3. Make bucket contents publicly accessible using a bucket policy
4. Register or use a custom domain with Route 53
5. Create an alias record pointing the domain to the S3 bucket
6. (Optional) Set up CloudFront distribution and SSL certificate via ACM
7. Push project to GitHub

## 📂 Project Structure

```
aws-static-site/
├── index.html       # Main landing page
├── error.html       # Custom error page
└── README.md        # Project documentation
```

## 🔗 Live Demo

http://marvinabiewa.com.s3-website.us-east-2.amazonaws.com/

## 🧠 What I Learned

- How to configure S3 for static site hosting
- How to manage custom domains with Route 53
- How to set public access policies safely
- Best practices for documenting and sharing cloud projects

## 📜 License

This project is licensed under the MIT License.
