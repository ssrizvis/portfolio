# Contact Form Setup Guide

## How to Make Your Contact Form Functional

### Step 1: Sign up for Formspree (Free)

1. Go to [https://formspree.io](https://formspree.io)
2. Click "Get Started" and create a free account
3. Verify your email address

### Step 2: Create a New Form

1. After logging in, click "New Form"
2. Give your form a name (e.g., "Portfolio Contact Form")
3. Copy the form endpoint URL (it will look like: `https://formspree.io/f/YOUR_FORM_ID`)

### Step 3: Update Your Portfolio

1. Open `index.html` in your portfolio
2. Find the contact form (around line 500+)
3. Replace `YOUR_FORM_ID` in the form action with your actual Formspree form ID
4. Update the `_next` field with your actual GitHub Pages URL

### Step 4: Deploy to GitHub Pages

1. Push your portfolio to GitHub
2. Enable GitHub Pages in your repository settings
3. Your form will be functional once deployed!

## Example of Updated Form Action:

```html
<form
  action="https://formspree.io/f/xpzgkqyz"
  method="POST"
  id="contact-form"
></form>
```

## Features Included:

- ✅ **Free to use** (up to 50 submissions per month)
- ✅ **No backend code required**
- ✅ **Spam protection** built-in
- ✅ **Email notifications** when someone submits the form
- ✅ **Form validation** on the frontend
- ✅ **Loading states** and success/error messages
- ✅ **Works with GitHub Pages**

## What Happens When Someone Submits:

1. Form data is sent to Formspree
2. You receive an email with the submission details
3. User sees a success message
4. Form is reset for another submission

## Troubleshooting:

- Make sure your GitHub Pages URL is correct in the `_next` field
- Check that your Formspree form ID is correct
- Verify your email address in Formspree settings

That's it! Your contact form will be fully functional once deployed to GitHub Pages.
