## Setup

### 1. Initate project
```sh
bun create vite app-name
```

### 2. Incorporated the Theme Palette:
```css
:root {
  --color-primary: #34C94B; /* Green */
  --color-black: #121212;    /* Black */
  --color-white: #FFFFFF;    /* White */
  --font-main: 'Poppins', sans-serif;
}
/* Optional: Define some global styles */
body {
  font-family: var(--font-main);
  background-color: var(--color-white);
  color: var(--color-black);
}
```