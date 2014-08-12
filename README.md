# WOW Hack 2014 Showcase site

## Develop

```bash
npm install
echo '{"user":"xxxx","pass":"yyyy"}' > auth.json #Where xxxx and yyyy should be replaced
gulp server
```

Visit [localhost:3000](http://localhost:3000) in browser.

Gulp tasks:
```bash
gulp        # Defaults to gulp server
gulp css    # Compile SCSS to CSS
gulp watch  # Watch and compile SCSS to CSS
gulp server # Start Express server and watch SCSS
```
