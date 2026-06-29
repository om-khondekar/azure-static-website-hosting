# Azure Static Website Hosting

## Project Overview

This project demonstrates how to host a static website on Microsoft Azure using **Azure Storage Account** and **Static Website Hosting**.

The project deploys a Mini Finance web application consisting of HTML, CSS, JavaScript, fonts, and images, making it publicly accessible through Azure's Static Website endpoint.

---

# Architecture

```
                    User
                      │
                      ▼
          Azure Static Website Endpoint
                      │
                      ▼
             Azure Storage Account
                      │
                      ▼
                $web Container
      ┌────────────────────────────────┐
      │ index.html                     │
      │ css/                           │
      │ js/                            │
      │ images/                        │
      │ fonts/                         │
      └────────────────────────────────┘
```

---

# Azure Services Used

* Azure Storage Account
* Azure Blob Storage
* Azure Static Website Hosting
* Azure Containers

---

# Project Workflow

### Step 1

Created a Storage Account.

### Step 2

Enabled Static Website Hosting.

Configuration:

* Index Document: `index.html`
* Error Document: `index.html`

---

### Step 3

Uploaded the complete project files to the `$web` container.

Uploaded folders:

* css
* js
* images
* fonts

Uploaded HTML pages:

* index.html
* profile.html
* wallet.html
* setting.html
* help-center.html
* transaction-detail.html

---

### Step 4

Accessed the generated Azure Static Website URL.

Successfully verified that:

* HTML loaded
* CSS loaded
* Images loaded
* JavaScript executed successfully

---

# Screenshots

## Storage Account

<img width="1918" height="1197" alt="Screenshot 2026-06-29 215352" src="https://github.com/user-attachments/assets/05af238e-13fa-4aa9-8f2a-1d0b177a343c" />


---

## Static Website Configuration

<img width="1918" height="1198" alt="Screenshot 2026-06-29 215434" src="https://github.com/user-attachments/assets/054ea715-42ec-4929-80cd-e85b0897bd29" />

---

## Web Container

<img width="1918" height="1197" alt="Screenshot 2026-06-29 215625" src="https://github.com/user-attachments/assets/fbbc2c30-6c20-423a-b739-0f6fb07937f4" />

---

## Website Output

<img width="1917" height="1087" alt="Screenshot 2026-06-29 215649" src="https://github.com/user-attachments/assets/96b091b1-e0cf-4402-9c5e-a533d683c5ef" />

---

# Challenges Faced

Initially, the website loaded without CSS styling because only the HTML files had been uploaded to the `$web` container.

The issue was resolved by uploading the complete folder structure including:

* css
* js
* images
* fonts

Once the folder hierarchy matched the project's relative paths, the website rendered correctly.

---

# Skills Demonstrated

* Azure Storage Account
* Azure Blob Storage
* Azure Static Website Hosting
* Azure Containers
* Static Website Deployment
* Frontend Hosting
* Troubleshooting Static Assets

---

# Learning Outcomes

Through this project I learned:

* Creating Azure Storage Accounts
* Configuring Static Website Hosting
* Understanding Blob Containers
* Deploying frontend applications
* Managing project folder structures
* Troubleshooting missing CSS and static assets

---

# Author

**Om Khondekar**

Aspiring DevOps Engineer
