# CBDAS-2310030407
# 🚀 Hosting a Static Website using Amazon S3

## 📌 Project Overview

This project demonstrates how to host a static website using Amazon S3. The website is built using basic HTML, CSS, and JavaScript and is deployed on AWS cloud using S3 static website hosting.

---

## 🛠️ Technologies Used

* Amazon S3 (Static Website Hosting)
* HTML
* CSS
* JavaScript

---

## 📁 Project Structure

```
project/
│── index.html
│── style.css
│── script.js
```

---

## 🪜 Steps to Deploy

### 1. Create S3 Bucket

* Create a bucket with a unique name
* Disable "Block all public access"

### 2. Upload Files

* Upload index.html, style.css, script.js

### 3. Enable Static Website Hosting

* Enable hosting in bucket properties
* Set index document as `index.html`

### 4. Set Bucket Policy

* Allow public read access using bucket policy

### 5. Access Website

* Use the S3 website endpoint URL to view the site

---

## 🌐 Website URL

```
http://projectbucket0505.s3-website-<region>.amazonaws.com
```

---

## 🔐 Security

* Only read access (s3:GetObject) is allowed
* No write or delete permissions are granted

---

## 🎯 Features

* Simple static webpage
* Button interaction using JavaScript
* Hosted on AWS cloud

---

## ⚠️ Note

* The bucket must be public for the website to be accessible
* The index file name must be `index.html`

---

## 🎓 Conclusion

This project shows how Amazon S3 can be used to host static websites in a scalable and cost-effective way.

---


