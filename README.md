# Vulcanized libxml2 v2.8.0

This project uses the [Heroku][heroku] [Vulcan][vulcan] build system to build a copy of `libxml2 v2.8.0` for use on Heroku.

## Build Command

The following build command has been successful on previous runs:

```bash
vulcan build --source="." --output="libxml2.tar.gz" --command "./configure --prefix=/app/vendor && make && make install" --verbose
```
