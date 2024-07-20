## Selecteur de Photos

A simple photo selector web application that allows users to select photos from a list. The total number of selected photos is displayed dynamically.

## Table of Contents

- [Demo](#demo)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Challenges and Learnings](#challenges-and-learnings)
- [Future Improvements](#future-improvements)
- [Contact](#contact)
- [License](#license)

## Demo

### Live Demo

Check out the live demo [here](https://nada-tb-beginner-projects.github.io/photo-selector/).

### Screenshots

![Photo Selector Demo](https://github.com/Nada-TB-beginner-projects/photo-selector/blob/master/Selecteur_photos.png)
*Photo selector in action*

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Nada-TB-beginner-projects/photo-selector.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd photo-selector
   ```

3. **Open the `index.html` file in your web browser:**

   - Double-click the `index.html` file.
   - Alternatively, you can open it through your browser's "Open File" option.

## Usage

1. **Open the Web Application:**
   - Open the `index.html` file in your web browser.

2. **Select Photos:**
   - Click on any photo in the list to select or deselect it.
   - The total number of selected photos is displayed at the bottom.

## Features

- Select and deselect photos.
- Display the total number of selected photos dynamically.
- Responsive design.

## Technologies Used

- HTML
- CSS
- JavaScript

## Project Structure

Outline of the project directory:

```plaintext
photo-selector/
├── css/
│   ├── style.css                  # Main CSS file
├── images/                        # Images used in the photo selector
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   ├── 5.jpg
│   ├── 6.jpg
├── js/
│   ├── main.js                    # JavaScript functionality
├── index.html                     # Main HTML file
└── README.md                      # Project documentation
```

## Challenges and Learnings

1. **DOM Manipulation:**
   - **Challenge**: Efficiently updating the DOM to reflect user interactions.
   - **Solution**: Used event listeners to toggle classes and update the displayed count dynamically.

2. **Event Handling:**
   - **Challenge**: Handling multiple events on a list of items.
   - **Solution**: Added event listeners to each list item to manage selection state.

3. **Styling:**
   - **Challenge**: Providing visual feedback for selected items.
   - **Solution**: Used CSS classes to change the background color of selected items.

## Future Improvements

- Add animations for selection and deselection.
- Improve the styling and user interface.
- Add the ability to filter or sort photos.

## Contact

For any questions or feedback, you can reach me at:

- GitHub: [Nada-TB](https://github.com/Nada-TB)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
