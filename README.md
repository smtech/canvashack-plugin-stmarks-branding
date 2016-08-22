# canvashack-plugin-stmarks-branding

General branding settings for St. Mark's school within Canvas

## Mobile Login Styling

Until the mobile login is [included in the Theme Editor](https://community.canvaslms.com/message/40630), we need to style it via actual CSS. It looks like things like button colors leak out into the mobile login, but to match the look and feel of the web login, we need a logo and a background color.

###### `stmarks-branding.js`
Setting the background color actually requires flippin' Javascript, since the page is badly laid out and there is no way to select `body` background without impacting other pages in Canvas.
