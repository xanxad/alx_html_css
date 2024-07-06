# Responsive Web Page

This project is a responsive web page that switches to a mobile version when the screen width is 480px or less. The design includes specific hover and active states for links and buttons, and ensures the content is centered and constrained to a maximum width.

## Features

- **Responsive Design**: The layout adjusts automatically for screens that are 480px wide or less.
- **Link Hover/Active State**: Links change color to `#FF6565` when hovered or active.
- **Button Hover/Active State**: Buttons have reduced opacity (`0.9`) when hovered or active.
- **Centered Content**: The main content area is centered and has a maximum width of 1000px.

## Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/xanxad/alx_html_css
   ```

2. Open the project directory:

   ```sh
   cd repository-name
   ```

3. Open `index.html` in your web browser to view the web page.

## CSS

The following CSS ensures the web page meets the specified requirements:

### Responsive Design

```css
@media (max-width: 480px) {
  /* Add your mobile-specific styles here */
}
```
