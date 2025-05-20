# Mailto QR Redirect Service

A simple service that automatically redirects users to their default email client using mailto: links. Built with vanilla JavaScript and HTML, optimized for deployment on Vercel.

## Features

- Automatic redirection to email client
- Works on both mobile and desktop browsers
- Fallback link if automatic redirection fails
- Clean, minimal interface

## Deployment

This project is ready to be deployed on Vercel. To deploy:

1. Push this repository to GitHub
2. Visit [Vercel](https://vercel.com)
3. Create a new project and import this repository
4. Deploy

No additional configuration is needed - it will work out of the box.

## Local Development

To test locally, you can use any static file server. For example, using Python:

```bash
# Python 3
python -m http.server 3000
```

Then visit `http://localhost:3000` in your browser.

## Customization

To customize the email parameters, modify the `mailtoUrl` in `/send/index.html`. You can adjust:
- Email address
- Subject
- Body content

## License

MIT 