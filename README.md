# maintain.community

Maintain is a community of people interested in how we care for and maintain different parts of our world.

This is the source code for our website.

## Run this locally

You will need:

- A Ruby environment
- Bundler (`gem install bundler`)

Install the dependencies and launch the development server with:

    script/server

The site will be available to browse at <http://0.0.0.0:4000>.

If you have `openssl` installed (comes by default on macOS, and most Linux variants) you can optionally generate self-signed SSL certificates, so you can browse the development server in HTTPS mode:

    script/generate-ssl-certificates

The SSL certificates will be picked up next time you run `script/server`. The site will be available to browse at <https://0.0.0.0:4000>.
