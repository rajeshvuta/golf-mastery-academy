# Golf Mastery Academy - Complete Golf Learning Website

A comprehensive, multi-page golf learning platform with lessons, club guides, tips, video resources, and community discussion forums.

## Features

✅ **Multi-Page Architecture** - Optimized for ad placement and monetization
✅ **Responsive Design** - Works on all devices
✅ **SVG Illustrations** - Animated club illustrations for each golf club
✅ **Discussion Forum** - Community engagement with Disqus integration
✅ **Comments on Every Page** - Increase user engagement
✅ **Professional Design** - Elegant, magazine-style aesthetic
✅ **SEO Friendly** - Proper heading structure and semantic HTML
✅ **Ad-Ready** - Multiple ad placement slots throughout

## Pages Included

1. **index.html** - Homepage with overview and quick start guide
2. **clubs.html** - Comprehensive guide to every golf club with illustrations
3. **discussion.html** - Community forum page
4. **styles.css** - Complete stylesheet
5. **script.js** - Interactive JavaScript features

## Additional Pages to Create

You'll want to create these additional pages following the same structure:

- **rules.html** - Complete golf rules guide
- **lessons.html** - Detailed lesson plans for all skill levels  
- **tips.html** - Tips and tricks collection
- **videos.html** - Curated video library

## Publishing to Free Hosting

### Option 1: GitHub Pages (Recommended - Completely Free)

1. **Create a GitHub account** at https://github.com
2. **Create a new repository**:
   - Click "New" or go to https://github.com/new
   - Name it: `golf-mastery-academy` (or your preferred name)
   - Make it Public
   - Don't initialize with README
3. **Upload your files**:
   - Click "uploading an existing file"
   - Drag all your HTML, CSS, and JS files
   - Commit the files
4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main → root → Save
5. **Your site will be live at**: `https://yourusername.github.io/golf-mastery-academy`

### Option 2: Netlify (Easy Drag-and-Drop)

1. Go to https://www.netlify.com/
2. Sign up (free account)
3. Drag and drop your entire folder
4. Your site is instantly live!
5. Get a free domain like: `your-site-name.netlify.app`

### Option 3: Vercel

1. Go to https://vercel.com/
2. Sign up with GitHub
3. Import your repository
4. Automatic deployment
5. Free custom domain: `your-site.vercel.app`

### Option 4: Cloudflare Pages

1. Go to https://pages.cloudflare.com/
2. Sign up (free)
3. Connect to Git or upload files
4. Instant deployment
5. Free with custom domain support

## Setting Up Disqus Comments

1. **Sign up** at https://disqus.com/
2. **Create a new site**:
   - Go to https://disqus.com/admin/create/
   - Enter your site name (e.g., "Golf Mastery Academy")
   - Choose a unique shortname (e.g., "golf-mastery-academy")
3. **Replace in all HTML files**:
   - Find: `YOUR_DISQUS_SHORTNAME`
   - Replace with your actual shortname
4. **Configure**: Complete the Disqus setup wizard

## Monetization Setup

### Google AdSense

1. **Apply** at https://www.google.com/adsense/
2. **Add your site** and verify ownership
3. **Replace ad placeholders** with actual AdSense code:
   ```html
   <!-- Replace this: -->
   <div class="ad-placeholder">728 x 90 Banner Ad</div>
   
   <!-- With your AdSense code: -->
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXX"></script>
   <ins class="adsbygoogle"
        style="display:block"
        data-ad-client="ca-pub-XXXXXX"
        data-ad-slot="XXXXXXXX"
        data-ad-format="auto"></ins>
   <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
   ```

### Affiliate Links

**Amazon Associates**:
1. Sign up at https://affiliate-program.amazon.com/
2. Replace video links and add product recommendations
3. Use your affiliate tracking ID

**Golf Equipment Affiliates**:
- Global Golf Affiliates
- PGA Tour Superstore Affiliate Program
- Golf Galaxy Affiliate Program
- TaylorMade Affiliate Program

## Customization Tips

### Change Colors
Edit `styles.css` and modify the CSS variables:
```css
:root {
    --primary-green: #1a4d2e;  /* Main brand color */
    --accent-gold: #d4af37;    /* Accent color */
    --deep-forest: #0f2818;    /* Dark color */
    /* ... */
}
```

### Add Your Logo
Replace the SVG logo in the navbar with your own image:
```html
<div class="logo">
    <img src="your-logo.png" alt="Your Logo" width="50" height="50">
    <span class="logo-text">Your Site Name</span>
</div>
```

### Add Google Analytics
Add before closing `</head>` tag:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## File Structure

```
golf-mastery-academy/
├── index.html          # Homepage
├── clubs.html          # Golf clubs guide
├── discussion.html     # Forum page
├── rules.html          # Rules (create this)
├── lessons.html        # Lesson plans (create this)
├── tips.html           # Tips (create this)
├── videos.html         # Video library (create this)
├── styles.css          # All styles
├── script.js           # JavaScript
└── README.md           # This file
```

## Best Practices for Monetization

1. **Don't overload with ads** - 3-4 ads per page maximum
2. **Strategic placement**:
   - Top of page (after header)
   - Middle of content (between sections)
   - End of content (before footer)
   - Sidebar (if you add one)
3. **Quality content** - More pages = more ad impressions
4. **Fast loading** - Optimize images and minimize scripts
5. **Mobile-friendly** - Most traffic comes from mobile

## SEO Optimization

Add to each page `<head>`:
```html
<meta name="description" content="Your page description here">
<meta name="keywords" content="golf, golf lessons, golf tips, learn golf">
<meta property="og:title" content="Golf Mastery Academy">
<meta property="og:description" content="Learn golf from beginner to pro">
<meta property="og:image" content="your-image.jpg">
```

## Support & Updates

- Add more content regularly to increase traffic
- Create blog posts on golf topics
- Update video links regularly
- Engage with community in forum
- Share on social media

## License

Free to use and modify for your golf learning platform.

---

**Good luck with your golf learning website!** 🏌️⛳

For questions or improvements, consider adding a contact form or email address.
