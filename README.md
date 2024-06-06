# dokku-install-chromium
A naive hack to get qpdf into a dokku deployment

# Installation
> dokku plugin:install https://github.com/wallyfoo/dokku-install-chromium.git install-chromium

All future deployments on this server will have chromium installed.

Once again, a hammer to solve a problem of getting an executable into my container. This is specifically to get chromium installed for the ChromicPDF dependency for an Elixir project.
