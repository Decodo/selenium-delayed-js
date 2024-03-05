<p align="center">
<a href="https://dashboard.smartproxy.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://i.imgur.com/opsHIEZ.png"</a>
</p>

## Dependencies

```http
bs4
webdriver_manager
selenium
extension >> extension.py
```

## Authentication

You can create, edit, and delete proxy users in our Dashboard > Residential > Proxy setup page.

## Delayed JS Selenium Scraper

This code is a script in Python that uses the selenium and BeautifulSoup libraries to scrape delayed Javascript elements.

The script uses the Chrome web browser, controlled by the selenium library, to navigate to the website and retrieve its source code. The source code is then parsed using BeautifulSoup to extract specific information.

In order to use a proxy, the code uses the "webdriver_manager" and "extension" libraries to install the chrome driver and configure the Chrome browser to use a proxy server. The credentials for the proxy server, username, password, endpoint, and port are passed as arguments to the "proxies" function from the "extension" library (extension.py).

