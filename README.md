### Running Seq inside a `Docker` container
```sh
docker run \
  --name seq \
  -d \
  --restart unless-stopped \
  -e ACCEPT_EULA=Y \
  -v /Users/vwfs/__SANDBOX/logs:/data \
  -p 6003:80 \
  datalust/seq:latest
```
