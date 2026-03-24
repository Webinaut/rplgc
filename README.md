# Royal Park Ladies Golf Club

Website: [Royal Park Ladies Golf Club](https://royalparkladiesgolfclub.com.au/)  
Github: [rplgc](https://github.com/Webinaut/rplgc)

## Description

Royal Park Ladies Golf Club plays at Royal Park Golf Course in Parkville, Melbourne, Australia. This static website replaces a Joomla website the club had for many years.

## Features

- [Astro](https://astro.build/) static website stored in a Github repo and hosted on Netlify.
- Uses the [Pico CSS](https://picocss.com/) framework (Customised SCSS version) - A minimalist and lightweight starter kit that prioritizes semantic syntax, making every HTML element responsive and elegant by default.
- [Swiperjs](https://swiperjs.com/) used for front page hero image slider.

## Organisation

- SCSS Files:
  - main.scss: load partials and define type selectors
  - themes\\\_custom-colors-rplgc.scss: custom color pallette
  - \_style.scss: global styles
- scoped SCSS definitions within component files
- Swiperjs script within front page layout file

### Structure

```
└── 📁src
    └── 📁components
        ├── ContactFormNetlify.astro
        ├── Email.astro
        ├── Footer.astro
        ├── FPImageStack.astro
        ├── FrontPageHeader.astro
        ├── Gallery-old.astro
        ├── Gallery.astro
        ├── Hamburger.astro
        ├── Header.astro
        ├── Location.astro
        ├── Logo.astro
        ├── Mail.astro
        ├── MobilePhone.astro
        ├── Navigation.astro
    └── 📁images
        └── 📁front-page
            └── 📁2026
                ├── (all)
            └── 📁image-stack
                ├── Chipping.jpg
                ├── IMG_0554.jpg
                ├── Premiers.jpg
                ├── Premiers2025.jpeg
                ├── Putting.jpg
            ├── (older images - unused)
        └── 📁gallery
            ├── (gallery page images)
        ├── Golf-Australia.jpg
        ├── IMG_0613.jpg
        ├── IMG_0616.jpg
        ├── Royal Park Ladies Logo - MS4.png
        ├── RPGCLogo.png
        ├── RPLGC final Syllabus 2025.png
        ├── VGLLogo.png
    └── 📁layouts
        ├── FrontPageLayout.astro
        ├── Layout.astro
    └── 📁pages
        ├── about.astro
        ├── contact.astro
        ├── gallery.astro
        ├── index.astro
        ├── membership.astro
        ├── syllabus.astro
    └── 📁scripts
        ├── menu.js
    └── 📁styles
        └── 📁themes
            ├── _custom-colors-rplgc.scss
            ├── README.md
        ├── _style.scss
        ├── global.scss
        └── my-swiper-styles.scss
```
