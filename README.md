# Inkwell Under Construction HTML Project

## Description

This project contains the HTML, Pure CSS (no libraries) and Javascript code to render and "Under Construction" web page for Inkwell with SEO optimization and reusable code modules. 

## HTML Imports with jQuery

The project utilizes jQuery, a popular JavaScript library, to make AJAX requests and fetch content from external files. The `$.get()` function is used to load the content of the external files asynchronously and insert it into specific sections of the main HTML file. In the provided example, metadata is imported into the `<head>` section and the footer is imported into a designated `<footer>` element.

## Why This Setup?

1. **Separation of Concerns:** By storing metadata and footer content in separate files, the codebase becomes more organized and manageable. Changes in metadata or footer content can be made independently without affecting the main HTML file.

2. **Code Reusability:** If you have multiple HTML pages that share the same footer or metadata, this approach allows you to easily reuse the same content across different pages, reducing redundancy.

3. **Efficient Loading:** Fetching the metadata and footer content asynchronously ensures faster page loading times since the browser can continue rendering the page while making the requests.

## Getting It Running

Follow these steps to set up the project and see the import in action:

1. **Prerequisites:**
   - Make sure you have a code editor installed on your computer (e.g., Visual Studio Code, Sublime Text, or Atom).
   - Install Python (if not already installed) for running a local web server.

2. **Clone the Project:**
   - Clone or download the project from the GitHub repository: [HTML Import with jQuery](https://github.com/your-username/html-import-with-jquery)

3. **Install a Web Server:**
   - Open your terminal/command prompt, navigate to the project folder, and run the following command:
     ```
     python3 -m http.server
     ```

5. **Access the Preview:**
   - Open your web browser and enter the following URL: `http://localhost:8000/index.html`
   - The main HTML file (`index.html`) will load in the browser, and the jQuery script inside it will import the footer content from `footer.html`.

6. **Verify the Import:**
   - Open the browser's developer console (usually by pressing F12 or right-clicking on the page and selecting "Inspect" or "Inspect Element").
   - Check for any errors in the console that may be related to the script or the import process.

Now you should see the imported footer content displayed within the designated `<footer>` element on the preview in your browser.