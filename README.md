# Deploying Portfolio on S3 Bucket 

This repository contains the code and configuration for deploying a portfolio website to an Amazon Web Services (AWS) S3 (Simple Storage Service) bucket. This mini-project is designed as part of the AWS Solutions Architect course, and it demonstrates the process of deploying a static website to AWS using S3.

**Live Link**: [Portfolio on S3 Bucket](http://mini.project.bucket.s3-website-us-east-1.amazonaws.com)

## Overview

In this mini-project, we deploy a portfolio website to AWS S3, a highly scalable and cost-effective storage service. The project showcases how to host a static website, making it accessible to the public via a user-friendly URL. AWS S3 is an ideal choice for hosting static websites, as it provides low-latency and reliable web hosting with seamless scalability.

## Getting Started

Follow these steps to deploy the portfolio website to an AWS S3 bucket:

1. **Clone this Repository:**
   ```bash
   git clone https://github.com/your-username/Deploying-Portfolio-on-S3-Bucket-AWS.git
   cd Deploying-Portfolio-on-S3-Bucket-AWS
   ```

2. **Configure AWS Credentials:**
   Ensure you have the AWS CLI configured with the necessary credentials. If not, you can set up your AWS credentials using the `aws configure` command.

3. **Deploy the Website:**
   - Upload the website files to your S3 bucket using the AWS CLI or the AWS Management Console.
   - Configure the bucket for static website hosting.

4. **Access Your Website:**
   Once the website is deployed, you can access it using the following URL: [Portfolio on S3 Bucket](http://mini.project.bucket.s3-website-us-east-1.amazonaws.com)

## Project Structure

- **index.html**: The main HTML file for the portfolio website.
- **css/**: Contains the CSS styles for the website.
- **images/**: Place your portfolio images in this directory.
- **js/**: JavaScript files used for website functionality.
- **404.html**: Custom 404 error page.

## Technologies Used

- **HTML/CSS**: Front-end development.
- **JavaScript**: For website interactivity.
- **Amazon S3**: Hosting the static website.
- **AWS CLI**: For deployment and management.

## Feedback and Issues

If you encounter any issues or have suggestions for improvement, please feel free to create an issue in this repository.

Thank you for exploring this mini-project and happy learning!

*Note: Don't forget to clean up AWS resources when you're done to avoid unnecessary charges.*
