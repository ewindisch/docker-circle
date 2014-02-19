Image that never stops building
-------------------------------

To make this work, you need to build this image twice and tag it as 'scratch'.
```
build -t scratch .
build -t scratch .
```

This technique would work tagged as something else, but you'd need two different
dockerfiles. By calling it 'scratch' we can do this with a single Dockerfile.
