# Wiremock Template

This is a wiremock mock server template with some initial json and xml endpoint mappings. For more information, visit https://wiremock.org/.

## How to use it?

Run this command to bring the wiremock server up:

```sh
docker-compose up -d
```

Now, check whether your server is up and running:

```shell
docker ps
```

You should see a running wiremock container.

## How to hit endpoints?

Defined endpoint mappings are reachable at http://localhost:8080.

See example in the `request.http` file.