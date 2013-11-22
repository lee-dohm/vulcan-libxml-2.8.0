# Vulcanized libxml2 v2.8.0

This project uses the [Heroku][heroku] [Vulcan][vulcan] build system to build a copy of [libxml2 v2.8.0][libxml2] for use on Heroku.

## Build Command

The following build command has been successful on previous runs:

```bash
vulcan build --source="." --output="libxml2.tar.gz" --verbose \
  --command "./configure --prefix=/app/vendor && make && make install"
```

[heroku]: http://www.heroku.com
[libxml2]: http://www.xmlsoft.org/index.html
[vulcan]: https://github.com/heroku/vulcan
