# React Router

## What is it?

It's a package that allows us to change the URL, making it _look like_ the user is visiting different pages, when they are _actually_ still on the same page. This is a common pattern in Single-Page Applications ( **SPA** s).

## So what does it do?

It takes care of two tasks that are traditionally accomplished by going to different pages.

1. It keeps track of what is supposed to happen, and which components should be rendered, when you visit specific URLs.
2. It updates the browser's history with those URLs.

The second piece happens automatically; the first part is what you have to set up. Setting up routes for the React router is very similar to setting up routes in Express. You define the same basic things: the path, and what should happen when that path is visited. The only difference is that it will do the routing _on the client_, without actually hitting your server.
