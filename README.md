# Login Form with Tilt Effect

This HTML file creates a login form with a unique tilt effect using CSS and JavaScript. The form has various visual enhancements, including glowing text, a border with a bulb glowing effect, and a torch light effect upon focus.

## HTML Structure

The HTML structure consists of:

- `<!DOCTYPE html>`: Declaration of the HTML version.
- `<html lang="en">`: HTML root element with the language set to English.
- `<head>`: Contains metadata and styles.
  - Metadata includes character encoding and the title of the page.
  - Inline CSS styles define the appearance and animations for various elements.
- `<body class="night-theme">`: The body of the page with a class for potential theming.

## CSS Styles

- **Reset Styles**:
  - Resets default margin, padding, and box-sizing for all elements.
- **Body Styles**:
  - Sets a dark grey background color with a transition effect.
  - Defines the font-family as Arial or sans-serif for fallback.
- **Login Container**:
  - Positions the login form at the center of the viewport.
- **Tilt Container**:
  - Defines a perspective for a 3D effect.
- **Login Form**:
  - Styles the login form with a transparent background for a glowing effect.
  - Adds a border with a glowing bulb effect, rounded corners, padding, and alignment.
  - Applies transitions for transformations, border color, and box shadow.
  - Uses preserve-3d to maintain 3D transformations and sets initial box-shadow for glowing.
- **Form Elements**:
  - Styles input fields and submit button with appropriate dimensions, colors, and transitions.
- **Glowing Title Effect**:
  - Applies a gradient background to the title for a glowing effect using text clipping and animation.
- **Torch Light Effect**:
  - Applies a box-shadow effect on focus within the form for a torch-like illumination.

## JavaScript Interactions

- **Tilt Effect**:
  - Calculates mouse position relative to the form and applies a 3D tilt effect accordingly.
  - Adjusts the glowing intensity of the border based on the mouse position.
- **Background Color Change**:
  - Changes the body's background color to a darker shade on mouse enter the form and resets it on mouse leave.

## JavaScript Implementation Notes

- `tiltContainer` and `loginForm` variables fetch relevant DOM elements by their IDs.
- Event listeners are added to the `tiltContainer` for mouse movement and to the `loginForm` for hover effects.
- The JavaScript calculates mouse positions, form rotations, and glowing effects.
- The body's background color changes on hover within the form.
