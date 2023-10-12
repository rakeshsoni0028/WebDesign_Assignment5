# SCSS Styling for Web Pages

This project demonstrates the use of SCSS (Sass) to style web pages effectively, showcasing various features and techniques to maintain consistency and flexibility in web design.

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [File Structure](#file-structure)

## Introduction

This project serves as a reference for using SCSS in web development. It highlights the use of variables, mixins, custom properties, functions, and more to create modular and maintainable stylesheets for web pages.

## Key Features

The SCSS code in this project makes use of several key features and techniques:

1. **Variables:**
   - Variables like `$primaryColor`, `$secondaryColor`, and `$fontSizeBase` store color codes and font sizes for consistent design and easy updates.

2. **Custom Properties (CSS Variables):**
   - Custom properties defined in `:root` allow for dynamic and consistent application of colors and values throughout the stylesheet.

3. **Interpolation:**
   - Interpolation is used to dynamically create CSS property names and values within mixins, making styles more versatile.

4. **Mixins:**
   - Mixins encapsulate styles for reuse across multiple selectors, promoting modular code and ease of maintenance.

5. **Nesting:**
   - SCSS nesting helps organize and simplify code structure, enhancing readability and targeting specific elements effectively.

6. **Import:**
   - The `@import` directive allows the inclusion of external SCSS files for reusing styles and variables defined in other files.

7. **Functions:**
   - SCSS functions like `calculateFontSize` are used to calculate values, such as converting pixel values to relative units.

8. **Placeholder Selectors:**
   - Placeholder selectors, defined with `%`, enable the definition of styles that can be extended by other selectors, reducing redundancy.

9. **Grid Layout:**
   - CSS Grid layout is employed to structure elements in a grid format, enhancing layout flexibility and alignment.

10. **CSS Property Manipulation:**
    - Various CSS properties, including `box-shadow`, `float`, `margin`, `padding`, and `font-family`, are used to style elements consistently and effectively.

11. **@extend:**
    - The `@extend` directive applies styles defined in placeholder selectors, promoting style inheritance and consistency.

## File Structure

- `common.scss`: Contains common styles, variables, functions, and mixins used across different parts of the project.
- `home.scss`: The home SCSS file that imports `common.scss` and defines the styles for the specific project.
- `products.scss`: The products SCSS file that imports `common.scss` and defines the styles for the specific project.

