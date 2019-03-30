# Main services and related files

On the server this holds a devel checkout of:

- https://github.com/telescopio-montemayor/ethernet-encoder-servo
- https://github.com/telescopio-montemayor/lx200-encoder-bridge
- https://github.com/telescopio-montemayor/python-lx200

Inside venv35 install *ethernet-encoder-servo* (cd into folder and then run pip install -e .)
Inside venv37 install *lx200-encoder-bridge* and *python-lx200* (same as above)


## Nginx

For some services we are usign nginx as a front for ssl, routing and some security.
There should be a file here named *users_nginx*, created for example with htpasswd.
