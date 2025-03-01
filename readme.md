# Iftarkar Prayer Timings Widget

This widget provides Iftar and Sehri Timings from major institutions in Kashmir, allowing users to select their preferred institution and view the corresponding timings. The widget is designed to be lightweight, responsive, and easy to integrate into any website.

The data is fetched from [Iftarkar](https://github.com/haideralipunjabi/iftarkar2024), a project managed by [Haider Ali Punjabi](https://github.com/haideralipunjabi/). The prayer timings are collected from major Islamic institutions in Kashmir, ensuring accuracy and reliability.

---

## Features

- **Dynamic Data Fetching**: The widget fetches the latest prayer timings from the Iftarkar API.
- **Institution Selection**: Users can select their preferred institution from a dropdown menu.
- **Persistent Preferences**: The selected institution is saved using `localStorage`, so the user's choice is remembered across sessions.
- **Responsive Design**: The widget is compact and adapts seamlessly to different screen sizes.
- **Easy Integration**: Adding the widget to your website is as simple as including a few lines of code.

---

## How to Add This Widget to Your Website

To integrate the prayer timings widget into your website, follow these steps:

1. Add the widget's CSS file to your HTML `<head>` section:
   ```html
   <!-- Link to the widget CSS -->
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/maroofmedia/iftarkar-widgets/widget.min.css">
   ```

2. Add a container element where the widget will be displayed:
   ```html
   <!-- Widget Container -->
   <div id="prayer-timings-widget"></div>
   ```

3. Include the widget's JavaScript file at the end of your HTML `<body>` section:
   ```html
   <!-- Include the JavaScript file -->
   <script src="https://cdn.jsdelivr.net/gh/maroofmedia/iftarkar-widgets/widget.min.js"></script>
   ```

That's it! The widget will automatically load and display the prayer timings for the selected institution.

---

## Customization

- **Styling**: You can customize the appearance of the widget by modifying the CSS file (`widget.min.css`) or overriding the styles in your own stylesheet.
- **Data Source**: If you want to use a different API or dataset, update the `fetch` URL in the JavaScript file (`widget.min.js`) to point to your desired source.

---

## Credits

- **Data Source**: [Iftarkar](https://github.com/haideralipunjabi/iftarkar2024) by [Haider Ali Punjabi](https://github.com/haideralipunjabi/).
- **Widget Development**: Managed by [Maroof Lone](https://www.marooflone.com/).
