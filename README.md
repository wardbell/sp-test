# Ward's sp-test github pages project

A github PROJECT pages repo where I can see and share a **mocked** SP SPA experience.

# Browse

Navigate to [https://wardbell.github.io/sp-test/](https://wardbell.github.io/sp-test/).

# Prepare

1. Clear everything out of the `sp-test` repo's `master` branch except 

    * the (hidden) `.git` folder
    * this `README.md`

1. Build with mocking configuration. Because this is a static web server, must build and copy the purely mocked SP.

1. Copy the entire `dist/app` folder into this project. 

1. Commit and push to github.

1. Wait briefly for github to re-gen the server.

# Revert

Remember that **this repo is PUBLIC.**

After testing **be sure to revert to this clean state with a `reset --hard`**.



# Does not refresh!

Remember that the address bar always has something _after_ the `https://wardbell.github.io/sp-test` that tells Angular where to navigate.

Because this is a static server and we cannot control 404 behavior, **you will get a 404 when you refresh the browser.**

The solution is to **trim the URL** in the browser address bar.