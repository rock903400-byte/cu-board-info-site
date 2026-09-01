# Agents Guide: 儲互社督導管理入口網

## Project Overview
- **Type**: Static Website (HTML/CSS/JS).
- **Structure**: Single page (`index.html`) with linked `style.css` and `app.js`.

## Key Conventions
- **Feature Search**: Search filtering in `app.js` relies on the `data-keywords` attribute of `.feature-item` elements in `index.html`.
- **Theming**: Theme state (`light`/`dark`) is controlled via the `data-theme` attribute on the `<html>` element and persisted in `localStorage`.

## Verification
- No automated build or test suite. Verify changes by opening `index.html` in a browser.
