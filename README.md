# Ronen Agranat blog

## Auto-deploy instructions

This blog is connected to Netlify. Netlify ops and hosting is free.

* Commit to `preview` to auto-deploy to preview endpoint.
* Commit to `master` to auto-deploy to master endpoint

Website in production at https://ronenagranat.com and https://www.ronenagranat.com

## Set up

* Install AWS command line tools: `brew install awscli && aws configure`
* Source `commands.sh` in your `.zshrc` file or similar

## Custom Minima theme

This Jekyll blog uses a custom theme.

* Fork the theme from here: https://github.com/ronen-agranat/miniscule

## How to test locally

    bloglocal

## How to deploy

    blogsync
