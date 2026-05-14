# event_fukui

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, single-page web application that displays upcoming events in Fukui, Japan.

## Demo

**https://github.com/code4fukui/event_fukui

> The application displays a responsive grid of event cards. Each card features a 16:9 event image, followed by the event date and title.

## Features

-   **Event Grid:** Displays events in a clean, responsive card-based grid suitable for both desktop and mobile.
-   **Automatic Filtering:** Fetches a complete event list and automatically displays only upcoming events.
-   **Direct Links:** Each event card links directly to the source page for more details.
-   **Lightweight:** Built with vanilla HTML, CSS, and JavaScript modules. No build step or external frameworks required.

## Running Locally

Because this project uses ES modules, it must be run from a local web server to function correctly.

1.  Clone the repository:
    ```sh
    git clone https://github.com/code4fukui/event_fukui.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd event_fukui
    ```
3.  Start a simple local server (e.g., using Python 3):
    ```sh
    python -m http.server
    ```
4.  Open your browser and navigate to `http://localhost:8000`.

## Data Source

Event data is fetched from a public CSV file hosted on GitHub Pages.

-   **CSV URL:** https://code4fukui.github.io/event_fukui_data/data/event_fukui.csv
-   **Data Repository:** [code4fukui/event_fukui_data](https://github.com/code4fukui/event_fukui_data)

## License

MIT License — see [LICENSE](LICENSE).