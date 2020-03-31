## Usage
1. Clone the repository and cd to it
```
git clone https://github.com/dteslya/mtproto-proxy
cd mtproto-proxy
```
2. Generate random secret key
```
openssl rand -hex 16
```
3. Put generated secret to `docker-compose.yml`
4. Edit `ports` variable in `docker-compose.yml` according to your environment (optional)
5. Run
```
docker-compose up -d
```

## Links
https://hub.docker.com/r/telegrammessenger/proxy/ 