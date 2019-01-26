Fork of [docker-nginx-brotli](https://github.com/fholzer/docker-nginx-brotli) with changed brotli repository, from [google/ngx_brotli](https://github.com/google/ngx_brotli) to [eustas/ngx_brotli](https://github.com/eustas/ngx_brotli)
...

# What is this?
This project is based on Alpine Linux, the official nginx image and an nginx module made by Google that provides brotli compression, which also is made by Google.

# How to use this image
As this project is based on the official [nginx image](https://hub.docker.com/_/nginx/) look for instructions there. In addition to the standard configuration directives, you'll be able to use the brotli module specific ones, see [here for official documentation](https://github.com/google/ngx_brotli#configuration-directives)
