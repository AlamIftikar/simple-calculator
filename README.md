# Elegant Calculator

Summary:
A stylish, client-side web calculator with a modern, glass-like UI. It supports basic arithmetic operations (+, -, *, /), clear (C), decimal input, and equals (=). The interface is responsive and visually refined with gradients, soft shadows, and a clean typography.

Key features:
- Modern, responsive UI with glassy card styling
- Gradient background and subtle motion on button hover
- Calculator supporting +, -, *, /, decimal, and equals
- Clear (C) functionality
- Equals button spans two columns for a compact layout
- Keyboard-friendly visual design (button focus ring for accessibility)

Setup instructions:
- No build steps required. This is a static HTML/CSS/JS file.
- To deploy locally, simply open index.html in a browser or serve with a local web server.

Usage instructions:
- Click the buttons on the screen to perform calculations.
- Use the C button to clear the current input and state.
- Use the decimal point button to input fractional numbers.
- Click = to compute results.

Technical details:
- HTML structure:
  - A single .calculator container with a .display and a .buttons grid.
  - Buttons include: C, /, *, -, 7, 8, 9, +, 4, 5, 6, -, 1, 2, 3, +, 0, ., =
  - The equals button has class equal to span two grid columns.
- CSS/Styling:
  - Uses CSS variables for color palette and shadows.
  - Glassy card look with rounded corners and soft shadows.
  - Buttons use gradients, hover effects, and a focus-visible outline for accessibility.
  - Responsive: width adapts to viewport with a max width constraint.
- JavaScript:
  - Computes simple arithmetic operations using a left-to-right evaluation pattern (no operator precedence beyond the calculator’s typical operation flow).
  - Handles number input, decimal points, operator input, and the equals operation.
  - Prevents divide-by-zero with an alert and reset.
  - Maintains internal state: currentInput, operator, previousValue.

Changes made in Round 2:
- Overhauled visual design to be more modern and stylish (gradient UI, glass-like card, typography improvements).
- Refined button styling with distinct operator, clear, and equal button treatments.
- Implemented a responsive layout that scales nicely on mobile devices.
- Preserved and kept the existing calculator logic, ensuring functionality remains intact while enhancing aesthetics.
- Added focus-visible accessibility cues and smoother hover/active states.

Deployment info (GitHub Pages):
- To deploy on GitHub Pages:
  1) Push this repository to GitHub.
  2) In the repository settings, enable GitHub Pages and set the source to the main branch (or gh-pages branch) containing index.html.
  3) Access the site at https://<your-username>.github.io/<repository-name>/

License:
MIT

">