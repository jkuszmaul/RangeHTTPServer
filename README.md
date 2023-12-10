This fork adds CORS support to play nice with foxglove.dev

# RangeHTTPServer

SimpleHTTPServer with support for Range requests

Quickstart:

    $ pip install rangehttpserver
    $ python -m RangeHTTPServer
    Serving HTTP on 0.0.0.0 port 8000 ...

# Alternatives

If you've found this, you may also be intersted in node's [http-server][1], which also includes support for Range requests.

[1]: https://www.npmjs.com/package/http-server

## Development

To release a new version:

    pip install --upgrade wheel setuptools twine
    python setup.py sdist bdist_wheel
    twine upload dist/*
