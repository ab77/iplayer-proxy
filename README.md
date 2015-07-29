# iplayer-proxy
`Docker` packaged smart DNS proxy to watch `BBC iPlayer` outside of the UK using `BIND` and `sniproxy`[n1]. This is a somewhat outdated clone of my other project, called [netflix-proxy](https://github.com/ab77/netflix-proxy).

# Instructions
The following is based on a standard Ubuntu Docker application image provided by `DigitalOcean`, but should in theory work on any Linux distribution with Docker pre-installed.

1. Head over to [Digital Ocean](https://www.digitalocean.com/?refcode=937b01397c94) to get $10 USD credit to create a Docker VM
2. Create a `Droplet` using `Docker 1.6.2` on `Ubuntu 14.04` (find in under Applications images).
3. Make sure you create the `Droplet` in the UK (LON) data center.
3. SSH to your `Droplet` and run the following command..
4. `cd /opt && git clone https://github.com/ab77/iplayer-proxy.git && cd iplayer-proxy && ./build.sh`
5. Point your DNS at the Droplet IP to watch content avialable on `BBC iPlayer` regardless of which country you are in.
6. Enjoy!
