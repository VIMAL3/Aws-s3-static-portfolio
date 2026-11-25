# Amazon S3 Static Portfolio Website

This repository contains a static HTML portfolio website deployed live using **Amazon S3 Static Website Hosting**, built as part of my AWS Cloud Internship.

## Key Objectives Covered
* **S3 Fundamentals:** Worked with S3 buckets, objects, and storage classes (S3 Standard, Standard-IA, Glacier).
* **Bucket Configuration:** Created a globally unique S3 bucket and uploaded static web assets (`index.html`).
* **Access Control & Permissions:** Disabled Block Public Access for web hosting and attached a custom JSON Bucket Policy (`s3:GetObject`) for read-only public access.
* **Static Website Hosting:** Enabled S3 Static Website Hosting and configured `index.html` as the index document.

## Live Architecture Flow
`User Browser` -> `Amazon S3 Static Website Endpoint` -> `S3 Bucket (index.html)`
