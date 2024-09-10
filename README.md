# BotBlocker.Pro JavaScript Snippet to Block Unwanted Visitors in Just a Minutes!

[![License](https://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub Issues](https://img.shields.io/github/issues/stopbot-net/smarturls.svg)](https://github.com/stopbot-net/smarturls/issues)

## Installation Guide

- Open your website’s HTML file.
- Paste the following JavaScript code just before the `</head>` tag, and replace `YOUR-API-KEY` with your BotBlocker.Pro API Key.
```html
<script defer data-key="YOUR-API-KEY" data-blocked-page="//google.com" src="https://cdn.jsdelivr.net/gh/botblocker-pro/lib/main.min.js"></script>
```
- You can also paste the code into every page (or into the master template) of your website just before the closing `</head>` tag. Make sure to update the value of data-blocked-page with the URL to which you want to redirect unwanted visitors. By default, unwanted visitors will be directed to [https://google.com](https://google.com).
- For information regarding visitor statistics, you can go to the [Blocker](https://botblocker.pro/blocker) page for details.

## Code Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Web Application</title>
  <!-- Include Embedded Code -->
  <script defer data-key="YOUR-API-KEY" data-blocked-page="//google.com" src="https://cdn.jsdelivr.net/gh/botblocker-pro/lib/main.min.js"></script>
</head>
<body>
<!-- Your web application content goes here -->
</body>
</html>
```

## License

This project is licensed under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license. See the [LICENSE](LICENSE) file for more details.
