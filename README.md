# Boogie Board Bungalow - Static Website

This is a static HTML/CSS/JavaScript version of the Boogie Board Bungalow beach house rental website. It has been converted from a React application to plain HTML, CSS, and JavaScript to simplify deployment and reduce dependencies.

## Features

- Responsive design
- Image gallery with lightbox
- Booking form with date validation
- Mobile-friendly navigation
- Animated elements
- Cross-browser compatibility

## Files Structure

```
boogie-board-bungalow/
├── index.html           // Homepage
├── rooms.html           // Rooms & Amenities page
├── attractions.html     // Local Attractions page
├── styles.css           // Main stylesheet
├── script.js            // JavaScript functionality
└── images/              // Image assets folder
    ├── header-beach.jpg
    ├── exterior.jpg
    ├── living-room.jpg
    ├── kitchen.jpg
    ├── master-bedroom.jpg
    ├── guest-bedroom.jpg
    ├── kids-bedroom.jpg
    ├── bathroom.jpg
    ├── beach.jpg
    ├── boardwalk.jpg
    └── downtown.jpg
```

## How to Deploy

This website consists of simple HTML, CSS and JavaScript files that can be deployed on any web server or hosting provider. Here are some options:

### Option 1: Traditional Web Hosting

1. Sign up for a web hosting service (like Bluehost, HostGator, DreamHost, etc.)
2. Upload all files to your hosting account using FTP or the hosting provider's file manager
3. The website will be live at your domain name

### Option 2: GitHub Pages (Free)

1. Create a GitHub account if you don't have one already
2. Create a new repository
3. Upload all your website files to the repository
4. Go to repository Settings > Pages
5. Set the source to your main branch
6. Your site will be published at `https://yourusername.github.io/repositoryname`

### Option 3: Netlify (Free)

1. Create a Netlify account at [netlify.com](https://www.netlify.com/)
2. Drag and drop your entire website folder to the Netlify upload area
3. Netlify will automatically deploy your site and provide a URL
4. You can configure a custom domain if desired

### Option 4: Vercel (Free)

1. Create a Vercel account at [vercel.com](https://vercel.com/)
2. Install the Vercel CLI or use the web interface
3. Deploy your site with a simple command or by connecting to your GitHub repository
4. Your site will be live with a Vercel URL

## Adding Images

Before deploying, you'll need to create an `images` folder and add the following images:

- header-beach.jpg (for the main header background)
- exterior.jpg (exterior of the beach house)
- living-room.jpg
- kitchen.jpg
- master-bedroom.jpg
- guest-bedroom.jpg
- kids-bedroom.jpg
- bathroom.jpg
- beach.jpg (local beach image)
- boardwalk.jpg (Ocean City boardwalk)
- downtown.jpg (downtown Ocean City)

You can use any appropriate beach house images as placeholders until you have actual photos of the property.

## Customization

### Colors

To change the color scheme, edit the CSS variables at the top of the `styles.css` file:

```css
:root {
  --primary-color: #1e88e5;
  --secondary-color: #00796b;
  --accent-color: #ff8a65;
  --text-color: #333;
  --light-color: #f8f9fa;
  --dark-color: #263238;
  --gray-color: #eceff1;
}
```

### Contact Information

Update the contact information in all three HTML files where the phone number, email, and address appear.

### Content

Edit the HTML files to update text content, images, and links as needed for your specific property.

## Browser Compatibility

This website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Need Help?

For customization assistance or troubleshooting, you can:

1. Refer to MDN Web Docs for HTML/CSS/JavaScript documentation
2. Use W3Schools for tutorials and examples
3. Hire a web developer for advanced customizations

---

&copy; 2025 Boogie Board Bungalow