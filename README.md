# Infinite Logo Slider

This project showcases an infinite logo slider that smoothly displays a continuous loop of business logos. The images flow seamlessly from right to left using HTML and CSS, creating an engaging and dynamic visual presentation.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Smooth, continuous scrolling of logos.
- Responsive design with seamless animation.
- Accessible images with `alt` text.

## Setup

1. Clone the repository or download the source code.

    ```shell
    git clone https://github.com/EstebanEscobar99/infinite-slider.git
    ```

2. Navigate to the project directory.

    ```shell
    cd infinite-slider
    ```

3. Open `index.html` in your browser to view the slider.

## Usage

1. Place your logo images in the `images` directory.
2. Update the HTML file to include your images, ensuring each image has an appropriate `alt` attribute.

    ```html
    <div class="slide"><img src="images/your-logo.png" alt="Your Logo"></div>
    ```

3. Customize the CSS file if needed to adjust the appearance and animation of the slider.

## File Structure

```graphql
infinite-slider/
├── index.html
├── styles.css
├── images/
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   └── 5.jpg
└── README.md
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/your-feature-name).
5. Open a pull request.

Please ensure your code adheres to the existing style guidelines and passes all linting and testing checks.

## License

This project is not licensed.
