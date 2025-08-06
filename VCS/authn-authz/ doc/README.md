# VCS Authn & Authz Strategy – Notification Documentation


<img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/9dbeda3b-e6a1-42c0-8c0e-890241abd4cc" />

---

##   Author Information

| **Author**   | **Created on** | **Version** | **Last updated by** | **Last edited on** | **Level** | **Reviewer**  |
|--------------|----------------|-------------|---------------------|--------------------|-----------|---------------|
| Tina Bhatnagar  | 28-07-25    | v1.0  |  Tina Bhatnagar |28-07-25     | Internal    | Rohit Chopra    |

---

## Table of Contents

 [Introduction](#introduction)
* [Pre-requisites](#pre-requisites)
* [Step-by-Step Setup Guide (Performed on GitHub)](#step-by-step-setup-guide-performed-on-github)

  * [Email Notification Setup](#email-notification-setup)

    * [Account Level Notification Setup](#account-level-notification-setup)
    * [Repository Level Notification Setup](#repository-level-notification-setup)
    * [Email Notification Summary](#summary)
  * [Slack Notification Setup](#slack-notification-setup)
* [Best Practices](#best-practices)
* [Conclusion](#conclusion)
* [Contact Information](#contact-information)
* [References](#references)


---

## 1. Introduction

This document is part of the **VCS Authn & Authz Strategy** and focuses on setting up notification systems in Version Control Systems like GitHub, GitLab, Bitbucket, and Azure DevOps. It includes the required pre-requisites, step-by-step configuration guides for *Email* and *Slack*, and best practices to ensure secure and effective alerting. 
For a detailed overview of notification concepts and background, refer to the introduction guide [here](https://github.com/Snaatak-Apt-Get-Swag/documentation/blob/scrum-104-sunny/VCS/Notification-System/Concept/README.md).

---

## 2. Pre-requisites

| **Requirement**               | **Description**                                               |
| ----------------------------- | ------------------------------------------------------------- |
| VCS Platform                  | GitHub, GitLab, Bitbucket, or Azure DevOps configured         |
| Admin Access                  | Required to create webhooks or configure notification rules   |
| Email Server or Chat Tool     | Configured for sending messages (e.g., SMTP, Slack, MS Teams) |
| API/Webhook Token             | For external integrations (if required)                       |

---

## 3. Step-by-Step Setup Guide 

This section explains how to configure *Email* and *Slack* notifications within *GitHub*. Other platforms follow similar flows, but all steps and screenshot placements below are GitHub-specific.

---

### Email Notification Setup

---

#### Account Level Notification Setup

Step 1: Go to your GitHub account settings
Click your *profile icon → Settings* from the top-right corner of GitHub.

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/5f9e5e6d-5c70-4974-970b-f3c035532fbb" />

---

Step 2: Open the Notifications tab
In the left sidebar, click *Notifications* to access email settings.

<img width="600" height="700" alt="image" src="https://github.com/user-attachments/assets/9c6ba9dc-aa48-49d9-a3ca-ebe5c545183a" />

---

Step 3: Set your default email address
Under Default notifications email, add or verify your preferred email address.

<img width="500" height="360" alt="image" src="https://github.com/user-attachments/assets/3b2dc401-ee69-4d9d-ba8b-ae48c491aec3" />

---

Step 4: Enable notifications for watched repositories
Under Watching, click **“Notify me: Email”** to receive emails about repositories you watch.

<img width="500" height="598" alt="image" src="https://github.com/user-attachments/assets/67135afc-c1ee-47a2-8f15-4f033d3a6b2f" />

---

Step 5: Enable participation and mention alerts
Under Participating, @mentions, click **“Notify me: Email”** to get emails when you're tagged or involved in threads.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/26854604-5557-406a-befb-2eccff504bbb" />

---

Step 6: Customize which events trigger emails
Click **Customize email updates**, then select the events you want:

* Pull Request reviews
* Pull Request pushes
* Comments on issues and PRs
* (Optional) Include your own updates

Click **Save** after selecting.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/ddcbac8e-5572-4f6f-a6cf-0358b4adbf4b" />

---

## 4. Repository Level Notification Setup

Step 1: Open the repository where you want push notifications
Go to the specific repository you want notifications from.

---

Step 2: Go to repository settings
Click the **Settings** tab in the repository navigation menu.

<img width="700" height="600" alt="image" src="https://github.com/user-attachments/assets/af221305-81bd-475e-bb7d-52fb648427e8" />

---

Step 3: Navigate to Email notifications
In the left menu under **Integrations, click** Actions → Email notifications*.

<img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/e77e9193-4395-484a-9f5c-19a7bb21ffed" />

---

Step 4: Configure the notification fields

 **Address**: Enter one or two space-separated email addresses
 **Approved header**: Leave blank unless using a mailing list
**Active**: Check this box to enable notifications

<img width="500" height="561" alt="image" src="https://github.com/user-attachments/assets/18b474cb-c54c-4af3-8438-2a7bb2cd4f71" />

---

Step 5: Save the configuration
Click **Setup notifications** to apply your changes.

<details>
<summary><b>Click to expand Screenshot</b></summary>

<img width="1147" height="348" src="https://github.com/user-attachments/assets/8bc9a08f-5309-4239-be19-81d0a6ded091" />

<img width="1063" height="403" src="https://github.com/user-attachments/assets/458e6bd4-14ad-456c-b16a-88b237266509" />
</details>

---
