# GetNoticed

Website and client preview sites for [getnoticed.net.au](https://getnoticed.net.au)

## Structure

```
index.html                          ← Main GetNoticed website
CNAME                               ← Custom domain config
businesses/
  butterworth-landscapes/
    index.html                      ← Preview site
  [client-name]/
    index.html                      ← Add new clients here
```

## Adding a new client preview

1. Create folder: `businesses/client-name/`
2. Add their `index.html`
3. Push to main branch
4. Live at: `preview.getnoticed.net.au/businesses/client-name`

## Setup

- Hosted on GitHub Pages
- Domain managed via Cloudflare DNS
- Email: hello@getnoticed.net.au → forwarded via Cloudflare Email Routing
- Contact form: Formspree
