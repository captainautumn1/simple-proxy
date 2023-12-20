# simple-proxy

Simple reverse proxy to bypass CORS, used by [movie-web](https://movie-web.app).
Read the docs at https://docs.movie-web.app/proxy

---

### features:
 - Deployable on many platforms - thanks to nitro
 - header rewrites - read and write protected headers
 - bypass CORS - always allows browser to send requests through it
 - secure it with turnstile - prevent bots from using your proxy

### supported platforms:
 - cloudflare workers
 - AWS lambda
 - nodejs
