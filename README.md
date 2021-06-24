# tran.vu

> Uses Netlify's [redirects](https://docs.netlify.com/routing/redirects/) as a URL shortening service.

## Adding a new short URL

Add to the `public/_redirects` file:

```
# redirects "tran.vu/foo" -> foo.com
/foo			https://foo.com/
```

## Optional: Use emojis

Encode the emoji and add that to `public/_redirects`

```
window.encodeURI("🚗");
// -> "%F0%9F%9A%97"
```

