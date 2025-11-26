Sneakers Product Page

A fully responsive product landing page inspired by the Sneakers brand.
Built using HTML, SASS, Bootstrap, and custom CSS.
Includes an image gallery, carousel for mobile, responsive navigation with a hamburger menu, and dynamic UI components.

📌 Features

Responsive navigation bar with hamburger toggle

Product image gallery (desktop)

Bootstrap carousel for mobile devices

Product description & pricing section

Quantity selector

Add-to-cart button

Built with SASS modular structure

Clean and scalable file organization 


🛠️ Technologies Used

HTML5

CSS3

SASS (.sass)

Bootstrap 5

SVG Icons

📂 Project Structure
.
├── index.html
├── Public
│   ├── css
│   │   ├── app.css
│   │   └── app.css.map
│   ├── images
│   │   ├── design
│   │   │   ├── desktop-design.jpg
│   │   │   ├── mobile-design.jpg
│   │   │   └── mobile-menu.jpg
│   │   └── images
│   │       ├── favicon-32x32.png
│   │       ├── icon-cart.svg
│   │       ├── icon-close.svg
│   │       ├── icon-delete.svg
│   │       ├── icon-menu.svg
│   │       ├── icon-minus.svg
│   │       ├── icon-next.svg
│   │       ├── icon-plus.svg
│   │       ├── icon-previous.svg
│   │       ├── image-avatar.png
│   │       ├── image-product-1.jpg
│   │       ├── image-product-1-thumbnail.jpg
│   │       ├── image-product-2.jpg
│   │       ├── image-product-2-thumbnail.jpg
│   │       ├── image-product-3.jpg
│   │       ├── image-product-3-thumbnail.jpg
│   │       ├── image-product-4.jpg
│   │       ├── image-product-4-thumbnail.jpg
│   │       └── logo.svg
│   ├── Pages
│   └── videos
└── Src
    └── Sass
        ├── _allModules.sass
        ├── app.sass
        └── modules
            └── landing_page
                └── _header.sass

📄 How It Works
1. Navigation Menu

Desktop: horizontal menu

Mobile: opens using a checkbox toggle (#check)

Uses icons for menu open/close

2. Product Gallery

Desktop: shows large product image + thumbnails

Mobile: thumbnails are hidden, Bootstrap carousel is shown instead

3. Product Details

Includes:

Title

Brand name

Description

Price with discount

Old price

Quantity selector ( + / 0 / - )

“Add to Cart” button

4. Responsive Behavior

SASS media queries handle layout changes

Carousel appears only on screens under 480px

Desktop layout shows image gallery side-by-side with text 


