# YellowTickell Website - Project Structure

## 📂 Complete File Structure

```
YellowTickell/
│
├── 📄 index.html                     # Homepage (Entry Point)
│
├── 📁 pages/                         # All internal HTML pages
│   ├── 📄 about.html                # About Us page
│   ├── 📄 products.html             # Products page (13 shirts)
│   ├── 📄 csr.html                  # CSR page
│   └── 📄 contact.html              # Contact page
│
├── 📁 assets/                        # All website assets
│   │
│   ├── 📁 css/                      # Stylesheets
│   │   └── 📄 style.css            # Main stylesheet (optimized)
│   │
│   ├── 📁 js/                       # JavaScript files
│   │   └── 📄 script.js            # Main script file
│   │
│   ├── 📁 images/                   # All images
│   │   ├── 🖼️ logo.png              # Company logo (80px desktop, 60px mobile)
│   │   ├── 🖼️ shirt1.JPG           # Product image 1
│   │   ├── 🖼️ shirt2.JPG           # Product image 2
│   │   ├── 🖼️ shirt3.JPG           # Product image 3
│   │   ├── 🖼️ shirt4.JPG           # Product image 4
│   │   ├── 🖼️ shirt5.JPG           # Product image 5
│   │   ├── 🖼️ shirt6.JPG           # Product image 6
│   │   ├── 🖼️ shirt7.JPG           # Product image 7
│   │   ├── 🖼️ shirt8.JPG           # Product image 8
│   │   ├── 🖼️ shirt9.JPG           # Product image 9
│   │   ├── 🖼️ shirt10.JPG          # Product image 10
│   │   ├── 🖼️ shirt11.JPG          # Product image 11
│   │   ├── 🖼️ shirt12.JPG          # Product image 12
│   │   └── 🖼️ shirt13.JPG          # Product image 13
│   │
│   └── 📁 videos/                   # Video assets
│       └── 🎥 bgvideo.mp4          # Homepage background video
│
└── 📁 docs/                          # Documentation
    ├── 📄 README.md                 # Main documentation
    ├── 📄 LOGO_FIX_GUIDE.md         # Logo troubleshooting
    └── 📄 PROJECT_STRUCTURE.md      # This file

```

## 📊 Statistics

- **Total Files**: 25
- **HTML Pages**: 5 (1 home + 4 internal)
- **CSS Files**: 1
- **JS Files**: 1
- **Images**: 14 (1 logo + 13 products)
- **Videos**: 1
- **Documentation**: 3

## 🗂️ Folder Organization

### Root Level
- **index.html** - Main entry point, stays at root for easy access

### Pages Folder
- All secondary HTML pages
- Clean URLs: `/pages/about.html`
- Proper relative paths to assets

### Assets Folder
Organized by file type:
- **css/** - All stylesheets
- **js/** - All JavaScript files
- **images/** - Logo and product images
- **videos/** - Background videos

### Docs Folder
All documentation and guides

## 🔗 Path Structure

### From Root (index.html):
```
assets/css/style.css
assets/js/script.js
assets/images/logo.png
assets/videos/bgvideo.mp4
pages/about.html
```

### From Pages (pages/*.html):
```
../assets/css/style.css
../assets/js/script.js
../assets/images/logo.png
../index.html
```

## ✅ Benefits of This Structure

1. **Clean Organization** - Easy to find files
2. **Scalable** - Easy to add new pages or assets
3. **Maintainable** - Clear separation of concerns
4. **Professional** - Industry-standard structure
5. **SEO Friendly** - Clean URL structure
6. **Performance** - Optimized asset loading

## 🎯 Key Features

- ✅ Logo: 80px (desktop), transparent background
- ✅ All images properly organized
- ✅ Proper relative path references
- ✅ Clean folder hierarchy
- ✅ Documentation included

---

*Last Updated: 2024-11-12*