# Product Menu with Favorites Feature

This project implements a dynamic product menu with collapsible categories and the ability to favorite products. The project is built with plain JavaScript, HTML, and CSS and interacts with a JSON API to fetch product data.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

The **Product Menu** displays products grouped by categories. Each category is collapsible, allowing users to hide or reveal products. Users can also favorite individual products, and the favorites will be saved in `localStorage`, allowing them to persist across page reloads. The favorites are displayed in a separate "Favorites" section.

## Features

- **Dynamic Product Fetching**: Products are fetched from an external JSON API and dynamically displayed in collapsible categories.
- **Favorites Management**: Users can add or remove products from their favorites list by clicking on a heart icon.
- **LocalStorage Persistence**: The favorites list is saved in `localStorage`, ensuring it persists across page reloads.
- **Responsive Design**: The layout adjusts for different screen sizes, with a mobile-friendly grid layout.

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the components.
- **JavaScript (ES6+)**: For dynamic behavior, including fetching data from the API and managing user interactions.
- **LocalStorage**: To persist user data (favorites).
- **ARIA Roles**: For accessibility improvements.

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://shruthibezgam.github.io/advanced-product-menu/
   ```

2. Navigate to the project directory:
   ```bash
    cd product-menu
   ```

## Usage
### Once you have the project running:

Browse the product categories.
Click on the category headers to expand or collapse the product lists.
Click on the heart icons to favorite/unfavorite products. The "Favorites" section will update accordingly.
Favorites are saved in localStorage and will persist even when the page is reloaded.