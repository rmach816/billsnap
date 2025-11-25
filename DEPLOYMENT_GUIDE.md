# BillSnap Website Deployment Guide

## ✅ Website Created Successfully!

Your BillSnap landing page has been created and pushed to GitHub at:
**https://github.com/rmach816/billsnap.git**

## 📋 What's Included

### Pages Created:
1. **index.html** - Professional landing page with:
   - Hero section with clear value proposition
   - Features showcase (6 key features)
   - How It Works (3-step process)
   - Pricing comparison (Free vs Premium)
   - Call-to-action sections
   - Fully responsive design

2. **privacy.html** - Comprehensive Privacy Policy including:
   - ✅ Apple App Store compliant
   - ✅ Google Play Store compliant
   - ✅ GDPR compliant (EU)
   - ✅ CCPA compliant (California)
   - Privacy-first messaging highlighting local-only data storage
   - Publicly accessible URL requirement met

3. **terms.html** - Complete Terms of Use including:
   - Subscription terms
   - Refund policy
   - User rights and responsibilities
   - Liability disclaimers
   - Apple & Google-specific terms
   - Dispute resolution

4. **support.html** - Support page with:
   - Contact information (help@billsnap.online)
   - Comprehensive FAQ (12+ questions)
   - Feature comparison table
   - Troubleshooting guides

### Additional Files:
- **styles.css** - Professional, responsive CSS styling
- **CNAME** - Custom domain configuration (billsnap.online)
- **404.html** - Custom 404 error page
- **README.md** - Website documentation

## 🚀 Next Steps to Enable GitHub Pages

### 1. Enable GitHub Pages
1. Go to https://github.com/rmach816/billsnap
2. Click **Settings** (top navigation)
3. Click **Pages** (left sidebar under "Code and automation")
4. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
5. Click **Save**

### 2. Configure Custom Domain
1. In the GitHub Pages settings (same page)
2. Under "Custom domain", enter: `billsnap.online`
3. Click **Save**
4. Wait for DNS check (may take a few minutes)

### 3. Configure Your Domain DNS (At Your Domain Registrar)

You need to configure DNS records at your domain registrar (where you bought billsnap.online):

#### Option A: Using A Records (Recommended)
Add these A records for `billsnap.online`:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

#### Option B: Using CNAME Record
If using `www.billsnap.online`, add CNAME:
```
www.billsnap.online → rmach816.github.io
```

Then add CNAME for apex domain:
```
billsnap.online → www.billsnap.online
```

### 4. Enable HTTPS
After DNS propagates (15 minutes to 24 hours):
1. Go back to GitHub Pages settings
2. Check **Enforce HTTPS**
3. Wait for SSL certificate to provision

## 🔗 URLs After Deployment

- **Main Site:** https://billsnap.online
- **Privacy Policy:** https://billsnap.online/privacy.html
- **Terms of Use:** https://billsnap.online/terms.html
- **Support:** https://billsnap.online/support.html

## ✅ App Store Requirements Met

### Apple App Store Requirements:
✅ Privacy Policy URL: https://billsnap.online/privacy.html
✅ Support URL: https://billsnap.online/support.html
✅ Marketing URL: https://billsnap.online
✅ Publicly accessible and professional
✅ Describes all data practices
✅ Describes all features

### Google Play Store Requirements:
✅ Privacy Policy URL: https://billsnap.online/privacy.html
✅ Contact information: help@billsnap.online
✅ Support website: https://billsnap.online/support.html
✅ Terms of Use: https://billsnap.online/terms.html
✅ Describes permissions and data usage

## 📱 Update App Store Listings

When submitting your app, use these URLs:

### For iOS (App Store Connect):
- **Marketing URL:** https://billsnap.online
- **Support URL:** https://billsnap.online/support.html
- **Privacy Policy URL:** https://billsnap.online/privacy.html

### For Android (Google Play Console):
- **Website:** https://billsnap.online
- **Email:** help@billsnap.online
- **Privacy Policy URL:** https://billsnap.online/privacy.html

## 🎨 Customization Tips

### To Add App Store Badges:
Replace the placeholder links in index.html:
```html
<!-- Update these links after your app is live -->
<a href="YOUR_APP_STORE_URL" class="btn btn-primary">
    <span>📱 Download on App Store</span>
</a>
<a href="YOUR_GOOGLE_PLAY_URL" class="btn btn-secondary">
    <span>🤖 Get it on Google Play</span>
</a>
```

### To Add Screenshots:
1. Create an `images` folder in the website directory
2. Add screenshot images
3. Update the phone mockup section in index.html

### To Update Pricing:
Edit the pricing section in index.html and support.html if you change subscription pricing.

## 🔍 Testing Checklist

Before going live, test:
- ✅ All pages load correctly
- ✅ All links work (internal and email links)
- ✅ Mobile responsiveness (test on phone)
- ✅ Privacy policy is accessible
- ✅ Terms of Use is accessible
- ✅ Support email link works (mailto:help@billsnap.online)
- ✅ Navigation works across all pages
- ✅ No broken images or styling issues

## 📊 Analytics (Optional)

To add Google Analytics or similar:
1. Get your tracking code
2. Add to the `<head>` section of each HTML file
3. Update privacy policy to mention analytics

## 🆘 Troubleshooting

### Site Not Loading After 24 Hours
- Check DNS propagation: https://dnschecker.org
- Verify A records or CNAME is correct
- Ensure GitHub Pages is enabled in settings

### Custom Domain Not Working
- Verify CNAME file contains: `billsnap.online`
- Check DNS configuration at your registrar
- Wait up to 24 hours for DNS propagation

### HTTPS Not Available
- Wait for DNS to fully propagate first
- Then enable "Enforce HTTPS" in GitHub Pages settings
- GitHub auto-provisions Let's Encrypt SSL certificate

## 📞 Support

If you need help with the website or deployment:
- **GitHub Pages Docs:** https://docs.github.com/en/pages
- **Custom Domain Guide:** https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## 🎉 You're All Set!

Your website is:
- ✅ Professionally designed
- ✅ Fully responsive
- ✅ App Store compliant
- ✅ Privacy-focused
- ✅ Ready to deploy

Just enable GitHub Pages and configure your DNS, and you'll be live at billsnap.online!

---

**Created:** October 26, 2025  
**Repository:** https://github.com/rmach816/billsnap.git  
**Domain:** billsnap.online  
**Support:** help@billsnap.online

