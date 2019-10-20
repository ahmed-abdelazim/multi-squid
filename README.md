# multi-squid
## How to use
- Make sure that git, docker and docker-compose are installed
- Clone the repo `git clone https://github.com/ahmed-abdelazim/multi-squid`
- Modify `Allowed_IPs.txt` to allow source ip's
- You can modify destination proxy by editing the config which named by port number
`cache_peer DEST_PROXY_IP parent DEST_PROXY_PORT 0 no-query no-digest`
- Finally run `docker-compose up -d`
