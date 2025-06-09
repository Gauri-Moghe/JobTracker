# Job Tracker – Daily Job Application Counter

A lightweight web-based tool to help you keep track of how many jobs you apply to each day. Designed to encourage consistency and organization during your job search.

## Project Overview

This project implements a **daily job tracking website** that allows users to increment a counter every time they apply to a job. The counter automatically resets each day and persists data locally in the browser.

No login, database, or backend required — everything is handled in the frontend using **HTML**, **CSS**, and **JavaScript**.

## Features

* One-click job counter.
* Automatically resets at midnight (based on the system clock).
* Stores count in browser using `localStorage`.
* Simple and responsive design.

## Folder Structure

```
JobTracker/
├── index.html       # Main webpage
├── styles.css       # Styling
└── script.js        # Core logic
```


## Demo

Try it live here:
 [https://gauri-moghe.github.io/JobTracker/](https://gauri-moghe.github.io/JobTracker/)


## How It Works

* On each click of the "Apply to a Job" button, the counter increases.
* The count is saved in `localStorage` and resets daily based on the device’s current date.
* Simple logic ensures state persistence and a smooth user experience without a backend.

## Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla)**
* **GitHub Pages** (for deployment)


## Setup & Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Gauri-Moghe/JobTracker.git
   cd JobTracker
   ```

2. Open `index.html` in any modern browser.

## Credits

**Developed by**: Gauri Shashank Moghe  

## License

This project is licensed under the **MIT License**.
