# cPanel Email Account Setup Guide

A guide to creating new email accounts in cPanel for future reference.

## Table of Contents
- [cPanel Email Account Setup Guide](#cpanel-email-account-setup-guide)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Steps to Create an Email Account](#steps-to-create-an-email-account)
  - [Optional Settings](#optional-settings)
    - [Setting Up Email Forwarding](#setting-up-email-forwarding)
    - [Configuring Email Clients](#configuring-email-clients)
  - [Testing the Email Account](#testing-the-email-account)

## Overview
This guide outlines the steps for setting up a new email account in cPanel. The example email account used is **sales@muriras.co.ke**.

## Steps to Create an Email Account

1. **Log in to cPanel**
   - Access cPanel by logging in through your hosting provider’s website.

2. **Go to the Email Accounts Section**
   - In the cPanel dashboard, locate and click on **Email Accounts** in the **Email** section.

3. **Create a New Email Account**
   - Click **Create** to add a new email account.
   - Select the desired domain (e.g., `muriras.co.ke`) from the "Domain" dropdown.
   - Enter **sales** as the username to create the email **sales@muriras.co.ke**.
   - Set a strong password for the account or use the password generator.

4. **Set Email Storage and Quota**
   - Assign a storage quota or leave it as “Unlimited” based on needs.

5. **Save the Email Account**
   - Click **Create** to finalize the setup of the new email account.

## Optional Settings

### Setting Up Email Forwarding
- To forward emails to another address, go to **Email Forwarders** in cPanel.
- Add a new forwarder for **sales@muriras.co.ke** and specify the target email address.

### Configuring Email Clients
- To access emails in an external client (Outlook, Gmail, etc.), locate **Connect Devices** in the cPanel email settings.
- Note the IMAP/POP3 and SMTP settings provided, and use them to configure your email client.

## Testing the Email Account
1. Send a test email to **sales@muriras.co.ke**.
2. Confirm that you can send and receive emails from the account.

---

This README serves as a quick reference guide for setting up and managing email accounts in cPanel.
