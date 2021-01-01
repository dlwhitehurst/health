# health
This repo demonstrates a simple Node.js scalable web application with a
health-check endpoint.

## Prerequisites
Building and running this application requires the following:

- node
- npm
- docker

## Build and Run
This application repository does not store dependency binaries and before the
application can be built and run, the node_modules folder needs to be set up.
Do this using Node Package Manager or npm.

```bash
npm install
```

If the dependency downloads succeed, you can run the server like so.

```bash
npm start
```

The server will be listening for requests on localhost and port 3000. You can 
test the application /health endpoint using cURL.

```bash
curl GET http://localhost:3000/health
```

## License

See [LICENSE](LICENSE) (MIT)
