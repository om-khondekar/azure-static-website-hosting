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

![Storage](images/storage-account.png)

---

## Static Website Configuration

![Static Website](images/static-website.png)

---

## Web Container

![Container](images/web-container.png)

---

## Website Output

![Website](images/website-output.png)

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
