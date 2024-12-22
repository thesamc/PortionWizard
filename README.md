# Rad Recipe Machine / PortionWizard (name in progress...)

A vibrant, retro-styled web application built with vanilla JavaScript that helps users scale recipe ingredients up or down. This interactive tool features a playful design with bold colors, dynamic animations, and practical functionality for recipe management.

## Features
- Dynamic recipe ingredient scaling
- Retro and cyber theme options
- Ingredient sorting functionality
- Export capabilities (download/clipboard)
- Interactive UI with animations
- Real-time calculations
- Responsive design
- Toast notifications

## Built With
- HTML5
- CSS3 (Custom Properties)
- Vanilla JavaScript
- No external dependencies

## Design System
Core styles managed through CSS variables:
```css
:root {
    --primary: #FF4D00;
    --secondary: #00FF94;
    --accent: #FFE600;
    --purple: #B94EFF;
    --blue: #00C2FF;
    --background: #FFFFFF;
    --black: #000000;
    --text: #000000;
}
```

## Project Structure
The application includes several key components:
- Recipe name input
- Serving size calculator
- Dynamic ingredient list
- Results display
- Export options
- Theme switcher

## Setup
1. Clone the repository
   ```bash
   git clone https://github.com/thesamc/rad-recipe-machine.git
   ```
2. Open index.html in your browser

No build process required as this is a static website.

## Features in Detail
### Recipe Scaling
- Input original recipe servings
- Specify desired servings
- Automatic quantity calculations
- Unit preservation

### Ingredient Management
- Add/remove ingredients dynamically
- Input validation
- Sort ingredients alphabetically
- Custom units support

### Export Options
- Download as text file
- Copy to clipboard
- Formatted output

## Responsive Design
The website is fully responsive across:
- Mobile: < 768px (simplified layout)
- Tablet: 768px and up
- Desktop: Full features

## Future Updates
Planning to add:
- Recipe saving functionality
- Multiple recipe storage
- Unit conversion
- Fraction support
- Recipe categories
- Print styling
- Recipe sharing

## Contact
- GitHub: [@thesamc](https://github.com/thesamc)
- LinkedIn: [Samuel Chutter](https://www.linkedin.com/in/samuel-chutter/)
- Email: samcwebdev@gmail.com

## License
This project is open source and available under the MIT License.
