# Portfolio Website

This repository contains the source code for my personal portfolio website hosted with AWS S3 and Route 53.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)

## Overview

This is a simple static website designed to showcase my projects and skills. It is hosted on AWS S3 for scalable storage and Route 53 for domain management.

## Technologies Used

- HTML
- CSS
- JavaScript
- AWS S3 (Simple Storage Service)
- AWS Route 53

## Deployment
To deploy this website on AWS S3 and Route 53, follow these steps:

Create an S3 bucket to host your website files.
Upload all the HTML, CSS, and JavaScript files to the S3 bucket.
Enable static website hosting on the S3 bucket.
Create a hosted zone on Route 53 and configure the domain name.
Create a record set to point to the S3 bucket.
Update the DNS records with your domain registrar to use Route 53.

For detailed instructions, refer to the AWS documentation on hosting static websites.