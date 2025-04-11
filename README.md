<<<<<<< HEAD
# dhrupal-patel.github.io
=======
# Personal Portfolio Website

A clean, modern, and responsive portfolio website inspired by Vance Banks' portfolio design.

## Features

- Modern and clean design
- Fully responsive for all devices
- Smooth scrolling navigation
- Project showcase section
- About section with work history and skills
- Contact section
- Animation on scroll for enhanced UX

## How to Customize

### Basic Information

1. Open `index.html` and replace the following:

   - "Your Name" with your actual name in the title, navigation, hero section, and footer
   - Update the personal description in the hero section
   - Replace the placeholders in the About section with your professional story
   - Update the work history with your actual employment history
   - Modify the skills section to highlight your actual skills

### Projects

For each project in the "Selected Work" section:

1. Replace the placeholder project names, descriptions and links
2. Add your project images to the `images` folder and update the URLs in the HTML

### Contact Information

1. Update the email address in the Contact section
2. Replace the LinkedIn profile URL with your own

### Styling

To change the color scheme:

1. Open `css/styles.css`
2. Edit the color variables in the `:root` section at the top of the file

```css
:root {
    --primary-color: #4a4a4a;     /* Main text color */
    --secondary-color: #2a2a2a;   /* Footer background, hover states */
    --accent-color: #3498db;      /* Buttons, links, highlights */
    --text-color: #333;           /* Body text */
    --light-text: #f5f5f5;        /* Text on dark backgrounds */
    --background: #ffffff;        /* Main background */
    --light-grey: #f4f4f4;        /* Section backgrounds */
    --dark-grey: #777;            /* Secondary text */
}
```

### Images

1. Create the following folders if they don't exist:
   - `images`

2. Add your project images and profile photos to the `images` folder

3. Update the image paths in the HTML:
   ```html
   <div class="project-image" style="background-image: url('images/your-image.jpg')"></div>
   ```

## How to Deploy

This is a static website that can be deployed to any web hosting service. Some popular options include:

- GitHub Pages (free)
- Netlify (free tier available)
- Vercel (free tier available)
- Amazon S3 (low cost)

## Viewing Locally

To view the website locally, simply open the `index.html` file in your browser.

## Credits

This portfolio template is inspired by [Vance Banks' portfolio website](https://www.vancedesignsproducts.com/).

## License

Feel free to use this template for your personal portfolio. 
>>>>>>> 727cb7a (Initial portfolio website)
