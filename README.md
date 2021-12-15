# Next Snap Pixel
 next-snapchat-pixel is a module for tracking Snapchat events on React/Next based applications. As Next.js runs on both, server and client side, there can be
 times that you have to handle Window object manually when adding modules from package managers. Next Snap Pixel does this for you.
 Just install and track your activities!

# How to use?

`npm install next-snapchat-pixel`

# Importing

`import NextSnapPixel from 'next-snapchat-pixel`

# Initializing

`NextSnapPixel.init('YOUR_PIXEL_ID')`

# Tracking

For tracking without any data use `NextSnapPixel.track('TRACK_TYPE')`;
For tracking with data(price,currency .etc) `NextSnapPixel.trackWithData('TRACK_TYPE', {DATA})`