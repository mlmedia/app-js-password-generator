# JavaScript Password Generator

This one-page application is a simple password generator which uses (vanilla) JavaScript to generate a random password with alpha-numeric characters, numbers, and special characters based on the options passed from the form.

The Password Generator can be seen here: https://demo.millionlightsmedia.com/password-generator/index.html.

## Learn / Adopt / Fork

All of the code is in the single `index.html` file. You can easily `View Source` to view all of the code in order to learn more about it. I try to use clear commenting to explain the code.

Also, feel free to adopt and adapt to make it your own. If you like, fork it and send over a pull request. Add or solve existing issues. It is open-source, after all.

## Code formatting with Prettier

Keep code style consistent across both applications by checking or applying formatting:

```bash
npx prettier --check "app-backend/**/*.{js,jsx,ts,tsx,json,css,scss,html,md}"

npx prettier --check "app-frontend/**/*.{js,jsx,ts,tsx,json,css,scss,html,md}"
```

To apply formatting in place:

```bash
npx prettier --write "app-backend/**/*.{js,jsx,ts,tsx,json,css,scss,html,md}"

npx prettier --write "app-frontend/**/*.{js,jsx,ts,tsx,json,css,scss,html,md}"
```

Consider installing the Prettier – Code Formatter extension in VS Code and enabling `"editor.formatOnSave": true` to format files automatically on save using the project’s `.prettierrc`.
