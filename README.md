# Staffy Puppy Website

A modern, fully responsive website for showcasing Staffordshire Bull Terrier puppies without any backend requirements.

## Features

✅ **No Backend Required** - Pure frontend HTML, CSS, and JavaScript
✅ **Landing Page** - Beautiful hero section with call-to-action
✅ **Available Puppies Section** - Showcases puppies directly below the landing page
✅ **Contact Integration** - Direct links to:
   - WhatsApp Messenger
   - Facebook Messenger  
   - Email

✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
✅ **Modern UI** - Beautiful gradients, animations, and hover effects

## Files Included

- `index.html` - Main website file
- `style.css` - Complete styling and responsive design
- `script.js` - Interactivity and smooth scrolling
- `README.md` - This file

## How to Use

### 1. Open the Website
Simply open `index.html` in any web browser. No server required!

### 2. Customize Contact Information

#### Update WhatsApp Link
Find this line in `index.html` (around line 165):
```html
<a href="https://wa.me/1234567890?text=Hi!%20I'm%20interested%20in%20learning%20more%20about%20your%20Staffy%20puppies." target="_blank">
```
Replace `1234567890` with your WhatsApp phone number (include country code).

#### Update Facebook Messenger Link
Find this line in `index.html` (around line 180):
```html
<a href="https://m.me/staffypuppy" target="_blank">
```
Replace `staffypuppy` with your Facebook page username or ID.

#### Update Email Address
Find this line in `index.html` (around line 195):
```html
<a href="mailto:info@staffypuppy.com?subject=Inquiry%20About%20Staffy%20Puppies&body=Hello,%0D%0A%0D%0AI'm%20interested%20in%20learning%20more%20about%20your%20available%20puppies.%0D%0A%0D%0AThank%20you!"
```
Replace `info@staffypuppy.com` with your actual email address.

#### Update Contact Details Section
Find the "Contact Details" section (around line 207) and update:
```html
<p><strong>Phone:</strong> +1 (234) 567-8900</p>
<p><strong>Email:</strong> info@staffypuppy.com</p>
<p><strong>Location:</strong> Your City, Your Country</p>
```

### 3. Customize Puppy Information

Each puppy card can be customized by editing the `index.html` file. Find the puppy cards section and update:
- Puppy name
- Age
- Gender
- Color
- Description
- Image URL

### 4. Update Images

The website uses external images from Unsplash. To use your own images:
1. Create an `images` folder in the website directory
2. Save your puppy photos as PNG or JPG files
3. Update the `src` attributes in the image tags from external URLs to local paths

Example:
```html
<img src="images/puppy1.jpg" alt="Puppy Max">
```

### 5. Customize Social Media Links

In the footer section (around line 230), update the social media links:
```html
<a href="https://facebook.com/staffypuppy" target="_blank">
<a href="https://instagram.com/staffypuppy" target="_blank">
<a href="https://wa.me/1234567890" target="_blank">
```

## How Contact Links Work

### WhatsApp
- Format: `https://wa.me/[PHONE_NUMBER]`
- Clicking the link opens WhatsApp (if installed) or web version
- Add your phone number with country code (e.g., +1234567890)

### Facebook Messenger
- Format: `https://m.me/[PAGE_ID_OR_USERNAME]`
- Opens Facebook Messenger conversation
- Replace with your Facebook page ID or username

### Email
- Format: `mailto:email@example.com`
- Opens default email client
- Pre-fills subject and body with inquiry message

## Responsive Features

The website is fully responsive and includes:
- Mobile-friendly navigation
- Touch-optimized buttons and links
- Flexible grid layouts
- Optimized image sizes

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera
- Mobile browsers

## Customization Tips

1. **Colors**: Edit the CSS variables in `style.css` (lines 9-16)
2. **Fonts**: The site uses system fonts for speed
3. **Layout**: Modify grid columns and spacing in the CSS
4. **Animations**: Adjust transition times in `style.css`

## Deployment

To deploy this website:
1. Upload all files to your web host
2. No database or backend configuration needed
3. Works with any static hosting: GitHub Pages, Netlify, Vercel, etc.

## Questions?

For any modifications or custom features, feel free to edit the HTML, CSS, and JavaScript files directly.

---

**Built with ❤️ for Staffy Puppy lovers!**
