# Scraper API Example

This is a simple example of how to use a Scraper API to extract content from a given URL. The scraper fetches various data such as headings, links, images, and metadata from the website and displays it using dropdown menus.
## Aims
We aim to show that this scraper API can be hosted on any platform and doesnot consume much of resources. This example is free for public to use, but only for learning and legal purposes.

## Features
- Input any URL to scrape.
- Extract headings (H1 to H6).
- Extract links from tags (anchor tags).
- Extract images from the page.
- Extract metadata such as title, description, and others.

## Prerequisites

- You will need an API key (Bearer token) for the Scraper API. Replace the token in the JavaScript code with your own.
- A basic understanding of HTML, JavaScript, and Tailwind CSS.

## Usage

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Enter the URL of the page you want to scrape in the input field.
4. Click the **Scrape Website** button.
5. The scraped data will be displayed in dropdown menus for you to choose from.

### Example

If you want to scrape a page, simply input the URL like `https://example.com` and click **Scrape Website**.

### How It Works

- When you enter a URL and click on the **Scrape Website** button, an API request is made to the Scraper API with the URL.
- The API fetches the data and returns various types of information such as headings, links, images, and metadata.
- This data is displayed in dropdown menus in the HTML page.

## Running the Application

Simply open the `index.html` file in your browser. This application doesn’t require a server setup, as it's just an HTML file with JavaScript.

### API Key

The API requires a **Bearer token** to access the scraping service. Which we have setup and already included in this example. 

## Try from commandline
``` Bash
curl https://webscraperapi-e.onrender.com/scrape?url=<Your Url> -H 'Authorization: Bearer tardMMsKLkcjfLYP0lHSpw4ZfD5Of4Hc'
```
