# Vixe's Personal Website

A personal website showcasing my portfolio and information, hosted on GitHub Pages.

## Description

This is a static website built with HTML, CSS, and JavaScript. The site includes multiple pages featuring a home page, contact information, and a people/team section. The website is designed to be responsive and includes various images and interactive elements.

## Project Structure

- `home.html` - Main landing page
- `contact.html` - Contact information page
- `people.html` - People/team showcase page
- `styles.css` - Main stylesheet
- `script.js` - JavaScript functionality
- `home/` - Images for the home page
- `contact/` - Images for the contact page
- `people/` - Images for the people page

## How to Run

Since this is a static website, you can run it in several ways:

### Option 1: Open directly in browser
Simply open any of the HTML files (e.g., `home.html`) directly in your web browser.

### Option 2: Using a local web server
If you want to test with a local server (recommended for development):

```bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js http-server (if you have it installed)
npx http-server

# Or using PHP's built-in server
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

### Option 3: GitHub Pages
The website is automatically deployed to GitHub Pages at `https://vixe.github.io` when changes are pushed to the main branch.

## How to Test

### Manual Testing
1. Open each HTML page in a web browser
2. Test navigation between pages
3. Verify that all images load correctly
4. Check that the CSS styling is applied properly
5. Test any JavaScript functionality
6. Test responsiveness on different screen sizes

### Browser Testing
Test the website in different browsers:
- Chrome
- Firefox
- Safari
- Edge

### Mobile Testing
Test the website on mobile devices or use browser developer tools to simulate mobile viewports.

## Development

To make changes to the website:
1. Edit the HTML, CSS, or JavaScript files
2. Test locally using one of the methods above
3. Commit and push changes to the repository
4. GitHub Pages will automatically deploy the updates

## Technologies Used

- HTML5
- CSS3
- JavaScript
- GitHub Pages for hosting

