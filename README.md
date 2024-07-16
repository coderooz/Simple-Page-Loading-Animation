# Simple Page Loading Animation

This project demonstrates a simple page loading animation using CSS only. It includes a centered block with a loading spinner and a title.

## Features

- **Title:** Displayed at the top of the page.
- **Loading Animation:** A spinner animation in the center of the page.
- **Responsive Design:** Centered content adjusts based on screen size.

## How to Use

1. Clone the repository: `https://github.com/coderooz/Simple-Page-Loading-Animation`
2. Open `index.html` in a web browser.


### Project Structure

```
project-folder/
│
├── index.html
├── style.css
└── README.md
```

### Code in the project
### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loading Animation Example</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Loading Animation</h1>
    <div class="loader"></div>
  </div>
</body>
</html>
```

### style.css

```css
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Center the content vertically and horizontally */
html, body {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f0f0f0;
}

.container {
  text-align: center;
}

h1 {
  font-family: Arial, sans-serif;
  font-size: 24px;
  margin-bottom: 20px;
}

.loader {
  border: 4px solid rgba(0, 0, 0, 0.1);
  border-radius: 50%;
  border-top: 4px solid #3498db;
  width: 40px;
  height: 40px;
  animation: spin 1s linear infinite;
  margin: 20px auto;
}

@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
``` 

## Credits

- CSS spinner animation inspired by various online examples.
- Designed and implemented by Coderooz [Ranit Saha].

## License

This project is licensed under the MIT License - see the LICENSE file for details.
