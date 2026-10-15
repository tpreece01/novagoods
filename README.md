# NovaGoods Stock Planner

A fictional UK retailer’s interactive demand and replenishment workspace.

## Run locally

This is a static, client-side application. Open `index.html` in a browser, or serve this folder with any static web server, for example:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the repository root to GitHub Pages whenever changes are pushed to `main`, and supports manual runs. In the repository's **Settings → Pages**, choose **GitHub Actions** as the build and deployment source if it is not already selected.

The app has no server or ChatGPT Sites runtime dependency. Its sample data and calculations run in the browser; saved decisions and settings use that browser's local storage. Product photos and fonts are loaded from external websites, so those visuals require an internet connection.

## Notes

- All company, employee, supplier and inventory information is fictional demonstration data.
- Purchase orders are simulated. The app does not contact suppliers or place real orders.
- Browser data is local to each browser and device. Clearing browser storage removes it.
