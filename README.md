# Google Play Console Reviews Visualization

This web project is a tool for visualizing user reviews from the Google Play Console. The page displays the reviews in a table format, along with various charts for easy data analysis. The user can enter CSV data to populate the table and charts.

## Table of Contents
- [Live Demo](#live-demo)
- [Getting Started](#getting-started)
- [Features](#features)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Live Demo

Check out the live demo of the project [here](https://roman-tsisyk.com/Google-Play-Console-Reviews-Visualization-Tool/).

### Screenshot
![Play Console Reviews Visualization](Play%20Console%20Reviews%20Visualization.png)

## Getting Started

To get started with the project, clone this repository to your local machine:

```sh
git clone https://github.com/RomanTsisyk/google-play-reviews-visualization.git
```

Navigate to the project directory:

```sh
cd google-play-reviews-visualization
```

Open `index.html` in your preferred web browser to view and interact with the project.

## Features

- Displays Google Play Console reviews in a table format.
- Visualizes data through various charts:
  - Pie Chart
  - Histogram
  - Line Chart
  - Heatmap
  - Bubble Chart
  - Scatter Plot
  - Box Plot
  - Bar Chart
  - Donut Chart
- Calculates and displays statistics such as average rating and number of reviews.

## File Structure

The project has the following file structure:

```
google-play-reviews-visualization/
│
├── index.html
└── README.md
```

## Technologies Used

- HTML
- CSS
- JavaScript
- [PapaParse](https://www.papaparse.com/) – for parsing CSV data
- [Plotly](https://plotly.com/javascript/) – for data visualization

## How to Use

1. Open `index.html` in your web browser.
2. Enter or upload your CSV data in the designated area.
3. The table will populate with the review data.
4. The charts will update automatically to visualize the data.
5. View the statistics section for insights like the average rating and total number of reviews.

### Example CSV Format

Ensure your CSV file has the following headers:

```
Package Name,App Version Code,App Version Name,Reviewer Language,Device,Review Submit Date and Time,Review Submit Millis Since Epoch,Review Last Update Date and Time,Review Last Update Millis Since Epoch,Star Rating,Review Title,Review Text,Developer Reply Date and Time,Developer Reply Millis Since Epoch,Developer Reply Text,Review Link
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the existing style and conventions.

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```sh
   git commit -am 'Add new feature'
   ```
4. Push to the branch:
   ```sh
   git push origin feature-branch
   ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
```

---

### Explanation of the Merge

- **Header & Intro Section:**  
  Both versions were nearly identical, so they have been merged with the added screenshot information.

- **Live Demo:**  
  The live demo URL from the `main` branch was kept and the screenshot section was added right after.

- **Getting Started, Features, and File Structure:**  
  These sections were merged as they were very similar.

- **Technologies Used:**  
  The list from the `main` branch was kept (which is the same as the one in the `add-styling` branch, with minor differences) so that it shows a complete list.

- **How to Use, Contributing, and License:**  