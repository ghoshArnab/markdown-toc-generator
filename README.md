# markdown-toc-generator

## Development

Build the image:

```
docker build . -t markdown-toc-generator:dev
```

Use the image for running the container:

```
docker run -it -v "$(pwd)":/dev markdown-toc-generator:dev bash
```

Run GHC in the container:

```
stack ghci
```