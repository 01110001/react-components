# react-components
## React, tailwind css --> plugin: daisyui

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx}", // this pattern assumes all your react components are in the src folder with .js or .jsx extensions
  ],
  theme: {
    extend: {},
  },
  plugins: [require("daisyui")],
}
```

