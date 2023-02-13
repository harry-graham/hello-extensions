# Google Chrome extension: Hello Extensions!

This is a demo Google Chrome extension built following the Chrome [Development Basics](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/) guide.

## How to Load Unpacked Extension

- Go to `chrome://extensions`
- Toggle "Developer Mode"
- Click "Load Unpacked Extension"

## Reloading the Extension

Click the reload button on the extension on the page above.

## Viewing console logs and errors

See: https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#logs

TLDR:

Add the following script to the relevant HTML file:
```
<script src="popup.js"></script>
```

Create a `popup.js` file and add the following code:

```
console.log("This is a popup!")
```

Refresh the extension, open the popup, right-click on the popup and inspect it. You'll see the logs under the Console panel.

## Errors

Any errors are displayed within the extensions page, on the extension (see the "Error" button).
