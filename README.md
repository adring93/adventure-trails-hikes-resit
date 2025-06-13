# Adventure Trails Hikes - Semester Project Resit 1

## Project Overview
This project is a resit submission for the Front-end Development 1 (FED1-24) Semester Project 1 at Noroff. The goal is to develop a static website for Adventure Trails Hikes, a business offering extreme hiking experiences in various countries, focusing on nature, culture, and sustainability. The target audience is college-educated professionals aged 18–35. The site has been built from scratch to meet the brief and improve on my original submission.

## Features
- **Pages**: 5 pages (Homepage, Hikes, Culture, Sustainability, Contact).
- **Design**: Responsive, accessible (WCAG-compliant), and visually appealing for young professionals, modeled after Charlie's Wanderings.
- **Content**: Highlights hiking experiences, cultural immersion, and eco-friendly practices, with prices and travel details.
- **SEO**: Includes meta tags and keywords for better search visibility.
- **Performance**: Images optimized to <200kb for fast loading, tested with Google PageSpeed Insights.

## Usage
- **Live Site**: [https://adring93.github.io/adventure-trails-hikes-resit/index.html](https://adring93.github.io/adventure-trails-hikes-resit/index.html)
- **Navigation**: Use the header menu button to access all pages (toggles on mobile via CSS).
- **Accessibility**: Navigate using keyboard (Tab key) for WCAG compliance.

## Project Structure
- `index.html`: Homepage with hero image, featured hikes, and a call-to-action section.
- `hikes.html`: Detailed list of extreme hikes with prices and cultural/sustainability details.
- `culture.html`: Cultural experiences tied to hiking trips (e.g., Peruvian Pachamama ceremony).
- `sustainability.html`: Eco-friendly practices of the business (e.g., community partnerships).
- `contact.html`: Static contact form with accessibility features.
- `styles.css`: External stylesheet with DRY principles and responsive design.
- `assets/images/`: Optimized images for hikes and culture (e.g., sunrise.jpg, peru.jpg).

## Development Process
- **Planning**: Used a GitHub Kanban board for milestones and tasks ([Kanban board link](https://github.com/users/adring93/projects/5)).
- **Design**: Created a style guide with earthy tones and clean typography, along with mobile and desktop layouts, documented in `design-document.pdf`.
- **Development**: Built 5 pages with semantic HTML and responsive CSS, ensuring WCAG compliance.
- **Testing**: Verified accessibility with WAVE, responsiveness across devices, and performance with Lighthouse. Adjusted for colorblind accessibility with a simulator.
- **Improvements from Original Submission**:
  - Enhanced Accessibility: Added WCAG-compliant contrast, alt text, ARIA labels, and keyboard navigation.
  - Improved Semantic HTML: Used `<article>`, `<nav>`, and proper heading structures.
  - Optimized Performance: Reduced image sizes for faster load times, aiming for <3 seconds.

## Credits
- **Assets**: Provided by Noroff (Adventure Trails Hikes Assets.zip), including images like peru.jpg, glacier.jpg, trail.jpg, logo.jpg, community.jpg, ecotravel.jpg, and cooking.jpg.
- **Pexels Images**:
  - save.jpg: Photo by Antoni Shkraba (https://www.pexels.com/photo/a-man-and-a-woman-putting-garbage-in-a-sack-7656995/).
  - iceland.jpg: Photo by Kate Sofi (https://www.pexels.com/photo/man-playing-piano-on-shallow-lake-in-iceland-14226922/).
  - peruseremony.jpg: Photo by Rajesh Kumar (https://www.pexels.com/photo/men-dressing-traditional-costume-during-festival-18263934/).
  - annapurna.jpg: Photo by Kate Sofi (https://www.pexels.com/photo/brunette-woman-sitting-on-swing-near-mountain-16290129/).
- **Additional Images**: Sourced from Pexels.com for various sections.
- **Fonts**: Open Sans and Playfair Display from Google Fonts.
- **Tools**: Squoosh for image optimization, GitHub for project management.
- **Image Optimization**: Images were optimized using Squoosh and TinyPNG to reduce file sizes while maintaining visual quality. The `sunrise.jpg` image was converted to a CSS background image to address initial loading issues.
- **Responsive Design**: The site utilizes media queries in `styles.css` to adapt the layout and font sizes for different screen sizes, ensuring a consistent experience across devices.

## License
This project is for educational purposes and not licensed for commercial use.
