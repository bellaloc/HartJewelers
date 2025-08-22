
---

## Features

- Responsive design (desktop, tablet, mobile)
- Product catalog with detailed views
- User login, registration, and password recovery
- Shopping cart and checkout pages
- Blog with various layouts
- Team member profiles
- Contact form with PHP backend for email
- Custom 404 error page

---

## Technologies Used

- HTML5, CSS3, JavaScript (ES6)
- Bootstrap framework
- Sass (optional)
- PHP for contact form handling
- jQuery and plugins (Slick, Owl Carousel, Swiper)
- Icon fonts (Themify, FontAwesome, Flaticon)

---

## How to Use

1. **Open the project folder `HartJewelers/website` in your code editor** to customize content and styles.
2. **Edit HTML files** to update text, images, and products.
3. **Modify styles** in `assets/css/style.css` or Sass files in `assets/sass` for advanced customizations.
4. **Add or replace images** in `assets/images` for products, banners, and team members.
5. **Configure the contact form** by editing `mail-contact.php` with your email settings.

---

## Site Testing & Development

### Running Locally with Live Server

To preview the site live on your local machine during development:

- **Option 1: Using VS Code Live Server extension**
  1. Open the `website` folder in VS Code.
  2. Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) if you don't have it.
  3. Right-click on `index.html` and select **Open with Live Server**.
  4. Your default browser will open a local server (usually `http://127.0.0.1:5500`), and you can see your site live.
  5. Changes you make will auto-refresh in the browser.

- **Option 2: Using Python HTTP Server**
  1. Open a terminal/command prompt.
  2. Navigate to the `website` directory.
  3. Run:
     - For Python 3:
       ```
       python -m http.server 8000
       ```
     - For Python 2:
       ```
       python -m SimpleHTTPServer 8000
       ```
  4. Open `http://localhost:8000` in your browser.

**Note:** PHP files (like `mail-contact.php`) require a PHP-enabled server. The above methods do NOT run PHP.

### Testing PHP Backend Locally

To test PHP scripts such as the contact form on your local machine, use:

- **XAMPP, WAMP, or MAMP** (depending on your OS)
  1. Install one of these PHP development environments.
  2. Place the entire `website` folder inside the `htdocs` (or equivalent) directory.
  3. Start Apache server from the control panel.
  4. Access your site at `http://localhost/website/index.html`.
  5. Test PHP features such as the contact form.

---

## Deployment Instructions

### Requirements
- Web server with PHP support (e.g., Apache, Nginx)
- PHP version 5.6 or higher
- Mail server configured on your hosting environment (for the contact form)

### Steps

1. Upload the entire `HartJewelers/website` folder to your web server's public directory (e.g., `public_html` or `www`).

2. Ensure `mail-contact.php` has proper permissions and your server supports PHP mail() function.

3. Set your domain or subdomain root to point to the folder containing `index.html`.

4. Access your live site in a browser.

5. Test the contact form to confirm emails are working.

---

## Notes

- The project is a front-end template with a simple PHP contact form backend.
- For full e-commerce functionality, integrate with a backend platform or CMS.
- Customize fonts, styles, and scripts to match your brand.
- Always backup your project and test changes locally before deployment.

---

## License
MIT License

---

If you have any questions or need further help with development or deployment, feel free to ask!
