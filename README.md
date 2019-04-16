# selenium-webdriver

Selenium is a browser automation library. Most often used for testing
web-applications, Selenium may be used for any task that requires automating
interaction with the browser.

## Installation

Selenium may be installed via npm with

    npm install selenium-webdriver-wa

Out of the box, Selenium includes everything you need to work with Firefox. You
will need to download additional components to work with the other major
browsers. The drivers for Chrome, PhantomJS, Opera, and Microsoft's IE and Edge
web browsers are all standalone executables that should be available on your
[PATH](http://en.wikipedia.org/wiki/PATH_%28variable%29). The SafariDriver
browser extension should be installed in your browser before using Selenium; we
recommend disabling the extension when using the browser without Selenium or
installing the extension in a profile only used for testing.

| Browser           | Component                          |
| ----------------- | ---------------------------------- |
| Chrome            | [chromedriver(.exe)][chrome]       |
| Internet Explorer | [IEDriverServer.exe][release]      |
| Edge              | [MicrosoftWebDriver.msi][edge]     |
| PhantomJS         | [phantomjs(.exe)][phantomjs]       |
| Opera             | [operadriver(.exe)][opera]         |
| Safari            | [SafariDriver.safariextz][release] |

### Note

This repository has been cloned from the original repository, based on version 2.53.3:

This workaround has been implemented to fix a version of the dependency
`xml2js` to make it compatible with old versions of node.