# readable-cloudflare-http-headers
Collection of all Cloudflare HTTP Request Headers without the pain. 💀

## 💡 Information

This collection includes the alpha3 code, country, city, state (if available) and a country-flag image in SVG format.

Collection was last updated on February 22, 2021.

## 🛠️ Usage 

Strip the hashed value from the HTTP request string to get the alpha3 code: 

```
$var = explode('-', $_SERVER['HTTP_CF_RAY'])[1];
```

Then do whatever you want with it. 🤷

Visit the official cloudflare [documentation](https://support.cloudflare.com/hc/en-us/articles/200170986-How-does-Cloudflare-handle-HTTP-Request-headers-) for more information.
