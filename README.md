# Chat Widget CDN

A simple, embeddable chat widget that can be added to any website via CDN.

## Usage

Add the following script tag to your HTML:

```html
<script
    src="https://cdn.jsdelivr.net/gh/querybee/chat-widget-cdn-public@v1.0.0/chat-widget.js"
    data-api-key="your-api-key-here"
></script>
```

### Basic Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>
    <!-- Your content here -->

    <!-- Chat Widget Script -->
    <script
        src="https://cdn.jsdelivr.net/gh/querybee/chat-widget-cdn-public@v1.0.0/chat-widget.js"
        data-api-key="your-api-key-here"
    ></script>
</body>
</html>
```

### Full Page Example

To render the chat widget as a full-page container:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat Widget</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: system-ui, -apple-system, sans-serif;
        }
        #chat-widget-container {
            height: 100vh;
            width: 100%;
        }
    </style>
</head>
<body>
    <div id="chat-widget-container"></div>

    <script
        src="https://cdn.jsdelivr.net/gh/querybee/chat-widget-cdn-public@v1.0.0/chat-widget.js"
        data-api-key="your-api-key-here"
    ></script>
</body>
</html>
```

## Configuration

Replace `your-api-key-here` with your actual API key.

## Demo

See `example.html` for a working demonstration.
