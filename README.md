# Dollar to Bitcoin SATS convertor - Web Component

This is a stand alone web component that can be dropped into any website.

The component fetches the latest price of Bitcoin from Coindesk and displays the current amount of SATS you can buy for one US dollar. One Bitcoin equals one hundred millions SATS.

The component has minimal styling and will inherit some existing styles from your website.

## Usage

Just add the `dollar-to-sats-web-component.js` file to your codebase. Import the script into your HTML and add the web component.

Available component attributes:

- background-color
- text-color
- full-width
- interval-update-seconds (how often do you want to refetch the price, must be at least 10 seconds or more)

Example:

```
<!DOCTYPE html>
<html>

<head>
  <title>Dollar to Bitcoin Sats Converter Web Comonent</title>
  <script src="dollar-to-sats-web-component.js"></script>
</head>

<body>
  <dollar-to-sats-web-component 
    background-color="#333" 
    text-color="#fff" 
    full-width="false"
    interval-update-seconds="60"
  ></dollar-to-sats-web-component>
</body>

</html>
```

