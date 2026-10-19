# Image Gallery

### Discover beautiful images with ease

A responsive image search application built with JavaScript and the Pixabay API. Search for images by keyword, browse a dynamic gallery, and explore full-size photos with a lightbox.

[**Live Demo**](#) · [**GitHub Repository**](https://github.com/IrinaV1/image-gallery)

## Tech Stack

<p align="left">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" alt="JavaScript" />
  </a>
  <a href="https://vite.dev/">
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  </a>
  <a href="https://pixabay.com/api/docs/">
    <img src="https://img.shields.io/badge/Pixabay_API-2EC66D?style=for-the-badge&logo=pixabay&logoColor=white" alt="Pixabay API" />
  </a>
</p>

**Libraries**

- [Axios](https://axios-http.com/) — HTTP requests.
- [SimpleLightbox](https://simplelightbox.com/) — image previews in a modal window.
- [iziToast](https://izitoast.marcelodolce.com/) — notifications.

## Features

- **Image Search** — search for images by keyword using the Pixabay API.
- **Dynamic Gallery** — display search results in a gallery layout.
- **Pagination** — load additional images without clearing existing results.
- **Image Lightbox** — open larger versions of images in a modal window.
- **Loading Indicator** — show loading feedback while fetching images.
- **Notifications** — display messages for search results, errors, and empty queries.
- **End-of-Results Handling** — notify users when all matching images have been loaded.
- **Smooth Scrolling** — automatically scroll to newly loaded images.
- **Responsive Layout** — adapt the gallery to different screen sizes.

## How It Works

1. Enter a search keyword.
2. Browse the images returned by Pixabay.
3. Click an image to view a larger version.
4. Select **Load more** to fetch the next page of results.
5. Continue exploring until the end of the collection.

## Getting Started

### Prerequisites

- Node.js
- npm
- A Pixabay API key

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/IrinaV1/image-gallery.git
   ```

2. Navigate to the project directory:

   ```bash
   cd image-gallery
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure your Pixabay API key according to your project's configuration.

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open the local URL displayed in the terminal.

## Project Modules

The application uses ES modules to separate API requests, rendering, and application logic.

- `pixabay-api.js` — handles requests to the Pixabay API.
- `render-functions.js` — creates gallery elements and manages the loader and pagination button.
- `main.js` — handles search submissions, pagination, notifications, and scrolling.

## Future Improvements

- Add image categories and search filters.
- Improve accessibility and keyboard navigation.
- Add automated tests.
- Further improve loading and error states.

## Author

**Irina V.**

[GitHub Profile](https://github.com/IrinaV1)

---

*Built as a JavaScript project to practice ES modules, asynchronous programming, API integration, and DOM manipulation.*
