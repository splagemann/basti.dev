# basti.dev

## Project Overview
This project contains the source code for the personal website of **Sebastian Plagemann**, hosted at [basti.dev](https://basti.dev).

It is a simple, static "vCard" style landing page that provides a brief biography, contact information, and links to social media profiles.

## Architecture & Technology
*   **Type:** Static Website
*   **Frameworks:**
    *   **HTML5:** Semantic markup (`itemscope`, `itemtype`).
    *   **Bootstrap:** Used for layout (grid system) and styling. Note that CSS is loaded asynchronously at the end of the body.
    *   **Bootstrap Icons:** Used for social media icons.
*   **Hosting:** Likely GitHub Pages (indicated by the `CNAME` file).

## Directory Structure
*   **`index.html`**: The main entry point for the website. Contains all content and embedded styles.
*   **`css/`**: Contains local copies of Bootstrap CSS and font files.
*   **`img/`**: Static image assets (profile picture, favicon).
*   **`talks/`**: Stores downloadable content, such as conference slides (e.g., SymfonyCon).
*   **`CNAME`**: Configuration file for the custom domain `basti.dev`.

## Development & Usage

### Running Locally
Since this is a purely static site with no build step, you can view it locally by simply opening the file in a web browser.

**Using a local server (recommended for path resolution):**
```bash
# Python 3
python3 -m http.server

# PHP
php -S localhost:8000
```
Then navigate to `http://localhost:8000`.

### Deployment
Changes pushed to the main branch are likely automatically deployed to the live site via the hosting provider's static site integration. Ensure `CNAME` is preserved to maintain the custom domain connection.
