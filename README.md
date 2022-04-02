# docs.maxstanley.uk

The source for docs.maxstanley.uk

## Developing Locally

To run this site locally and test any changes run the following commands.

To prepare the repository for running.

```bash
git submodule update --init --recursive
cd themes/hugo-geekdoc
npm install
npm run build
```

To run the test server.

```bash
docker-compose up -d
```
