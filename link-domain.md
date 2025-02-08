# How to Link Your Domain to Shopify Using cPanel

## Overview
This guide will help you connect your domain to Shopify using cPanel so visitors can access your store through your custom domain.

## What You Need
- Access to your **cPanel account**.
- A **Shopify store**.
- A **custom domain** you want to use.

## Step 1: Log in to cPanel
1. Open your hosting provider’s cPanel login page.
2. Enter your **username** and **password**.
3. Click **Log in**.

## Step 2: Update Your DNS Records
1. In cPanel, find and open the **Zone Editor** or **DNS Settings**.
2. Select your domain and click **Manage**.
3. Update the following records:
   - **A Record**:
     - Name: `@` or your domain name (e.g., `example.com`)
     - Value: `23.227.38.65` (Shopify's IP address)
   - **CNAME Record**:
     - Name: `www`
     - Value: `shops.myshopify.com`
4. Save the changes and wait a few hours for them to take effect.

## Step 3: Verify Your Domain in Shopify
1. Log in to your **Shopify admin**.
2. Go to **Settings > Domains**.
3. Click **Connect existing domain**.
4. Enter your domain name (e.g., `example.com`) and click **Verify Connection**.
5. If everything is set up correctly, Shopify will confirm the connection.

## Step 4: Set Your Domain as Primary
1. In **Shopify admin**, go to **Settings > Domains**.
2. Select your custom domain and click **Set as Primary**.
3. Enable **Redirect all traffic to this domain**.

## Conclusion
Once your DNS settings update, your custom domain will work with Shopify. If you run into problems, check your DNS settings or contact Shopify support.

---
