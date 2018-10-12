# First things first

Pull requests are welcome. However, if you have an idea how to improve the project (fix a bug, implement a new feature etc.), create an issue first so that we can discuss it.

This project is aimed to remain backwards compatible. This means that changes should not break existing implementations or change the public API of the library. All current tests should pass after making changes. Also, the promise of this project is to keep the core API small and simple.

# Run tests

```bash
lein test
```

# Compile examples project

Start ClojureScript -> JS autocompile:

```bash
cd examples/src
lein figwheel
```

Start web server:

```bash
cd examples/resources/public
python -m SimpleHTTPServer 8000
```

Now point your browser to http://localhost:8000/index_dev.html

# Update API DOC

```bash
lein codox
```