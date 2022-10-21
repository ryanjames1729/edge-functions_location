# Edge Functions on Netlify
## Starting Out
This repo is a sandbox for me to learning how to use edge functions. After reading through the [blog post](https://whitep4nth3r.com/blog/add-personalization-to-static-html-with-edge-functions-no-browser-javascript/) by `whitep4nth3r`, I decided to see how I could do it too.

## What Happens
The way this works is that when you append `?method=transform` the edge function that is set up searches for that to be appended. If it finds that in the URL, it returns the geo location that can be found in the context object.

Of course you need to write a JS file for your edge functions and use a .toml file in your Netlify setup.

Want to see it work? Try out [edge functions](https://whitep4nth3r.com/blog/add-personalization-to-static-html-with-edge-functions-no-browser-javascript/) for yourself.