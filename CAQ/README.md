# KhanProTech Website

This is a professional website for KhanProTech to sell high-performance gaming computers and components. The website is built with HTML, CSS, and JavaScript, following a clean and modern design approach.

## Features

- Responsive design that works on all devices
- Product catalog with filtering by categories
- About Us section highlighting company strengths
- Customer reviews section
- Contact form with validation
- Modern and tech-focused design

## Structure

- **Home Page**: Features a hero section with a tagline and call-to-action buttons
- **Product Catalog**: Displays products in categories (Ready-made PCs, Gaming Computers, PC Components, Laptops)
- **About Us**: Company information and unique selling points
- **Customer Reviews**: Testimonials from satisfied customers
- **Contact Section**: Contact form and information

## Customization

### Changing Content

1. Open `index.html` to modify the main content of the website
2. Update product information, company details, and contact information as needed
3. Replace the placeholder SVG images in the `images` folder with your actual product images

### Styling

1. The main styling is in `css/styles.css`
2. Color scheme can be modified by changing the CSS variables at the top of the file:
   ```css
   :root {
       --primary-color: #0066cc;
       --secondary-color: #003366;
       --accent-color: #00aaff;
       --dark-color: #1a1a1a;
       --light-color: #ffffff;
       --gray-color: #f4f4f4;
       --text-color: #333333;
   }
   ```

### Adding Products

To add more products to the catalog:

1. Copy an existing product card in the `index.html` file
2. Update the product details (name, specifications, price)
3. Add the appropriate data-category attribute for filtering
4. Add a corresponding product image in the `images` folder

## Deployment

This website can be deployed to any web hosting service. Simply upload all files and folders to your hosting provider.

## Next Steps

1. Replace placeholder SVG images with actual product photos
2. Add real customer reviews and testimonials
3. Connect the contact form to a backend service for email processing
4. Add e-commerce functionality for online purchases
5. Implement a content management system for easier updates

## Credits

- Fonts: Google Fonts (Montserrat, Roboto)
- Icons: Font Awesome

## License

This project is created for KhanProTech and is not licensed for public use without permission.