# Nextcloud Talk (AIO)

This app uses the official Nextcloud All-in-One master container.

It is configured to start with a Talk-focused setup and sets:
- `NEXTCLOUD_STARTUP_APPS=spreed` (Talk app)
- reverse-proxy mode with `APACHE_PORT=11000`

Open the app URL to access the AIO setup interface first, then finish the Nextcloud installation wizard.
