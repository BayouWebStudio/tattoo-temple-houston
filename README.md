# Tattoo Temple Houston Website

A professional website for Tattoo Temple Houston, a premium tattoo and piercing studio located at 3346 E TC Jester Blvd, Houston, Texas 77018.

**Note: Studio closes March 2027**

## Features

- **Dark, Professional Design** - Modern tattoo shop aesthetic with gold accents
- **Mobile Responsive** - Optimized for all devices
- **Artist Galleries** - Showcase each artist's work with Instagram integration
- **Google Maps Integration** - Easy location finding
- **Smooth Scrolling** - Professional user experience
- **Instagram Booking** - Direct links to artist profiles for appointments

## Artists Featured

1. **Raul Wesche** (@weschetattoo) - Owner, Geometric/Sacred Geometry specialist
2. **Madeline B.** (@sailor.doom.tattoos) - Anime & Kawaii tattoos
3. **Kris (Chloe Kristensen)** (@krisxmoon) - Art teacher & tattoo artist
4. **Julia Claire (Juju)** (@juju.brilliart) - Professional body piercer

## GitHub Pages Setup Instructions

### 1. Create GitHub Repository

```bash
# Create a new repository on GitHub called 'tattoo-temple-houston'
# Clone the empty repository locally
git clone https://github.com/YOUR_USERNAME/tattoo-temple-houston.git
cd tattoo-temple-houston

# Copy all files from this directory to your repo
cp -r /Users/wescheclaw/.openclaw/workspace/tattoo-temple-site/* .

# Add all files
git add .
git commit -m "Initial commit: Tattoo Temple Houston website"
git push origin main
```

### 2. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select **"Deploy from a branch"**
5. Choose **"main"** branch and **"/ (root)"** folder
6. Click **Save**

### 3. Custom Domain Setup (Optional)

If you want to use the custom domain `houstontattootemple.com`:

1. Create a file called `CNAME` in the root directory:
   ```
   houstontattootemple.com
   ```

2. Configure your domain DNS:
   - Add a CNAME record pointing `houstontattootemple.com` to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub's IP addresses:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

3. In GitHub Pages settings, add your custom domain and enable HTTPS

### 4. Site Structure

```
tattoo-temple-site/
├── index.html          # Main website file
├── css/
│   └── style.css      # All styles and responsive design
├── js/
│   └── script.js      # Interactive features and animations
├── images/            # Artist portfolio images from Instagram
│   ├── raul_1.jpg through raul_4.jpg
│   ├── madeline_1.jpg through madeline_2.jpg
│   ├── kris_1.jpg through kris_4.jpg
│   └── juju_1.jpg through juju_6.jpg
├── favicon.svg        # Site icon
├── favicon.ico        # Fallback icon
└── README.md         # This file
```

### 5. Updating Content

To update the website:

1. Make changes to the files
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```

3. Changes will automatically deploy to GitHub Pages within a few minutes

### 6. Instagram Photos

The website includes recent photos from each artist's Instagram account, fetched using the Meta Business Discovery API. To update photos, you'll need to run the `fetch_instagram_photos.py` script with proper API credentials.

## Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **Fonts**: Google Fonts (Playfair Display + Inter)
- **Icons**: Font Awesome 6.4.0
- **Responsive**: Mobile-first design with CSS Grid/Flexbox
- **Performance**: Optimized images, lazy loading, smooth animations
- **SEO**: Semantic HTML, meta tags, proper alt attributes

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 Tattoo Temple Houston. All rights reserved.

## Support

For website updates or technical issues, contact the site administrator.

---

**Closing Notice**: Tattoo Temple Houston will be closing in March 2027. Book your appointments with our artists soon!