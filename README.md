# blazorxtailwindcss
Sample project for testing Blazor WASM using TailwindCSS

Install Tailwind CLI with npm:
`npm install -g tailwindcss`

Start tailwind: 
`npx tailwindcss -i ./Styles/tailwind.css -o ./wwwroot/css/gen.css --watch` 

This should regenerate the output CSS everytime you change a tailwind class inside of a razor file. But it doesn't.

Run blazor project with hot reload enabled.
