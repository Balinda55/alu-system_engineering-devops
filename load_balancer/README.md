# Load balancer

- `0-custom_http_response_header`: configures Nginx on a new Ubuntu machine with a custom `X-Served-By` header set to the server's hostname.
- `1-install_load_balancer`: installs and configures HAProxy on lb-01 to send traffic to web-01 and web-02 with roundrobin.
