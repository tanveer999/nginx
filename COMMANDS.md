1. check the nginx.conf for any syntax mistakes
```
nginx -t
```

2. reload nginx after nginx.conf changes
```
nginx -s reload
```

The -s option is used for dispatching various signals to NGINX. The available signals are stop, quit, reload and reopen