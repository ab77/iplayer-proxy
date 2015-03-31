# iplayer-proxy
Docker packaged smart DNS proxy to watch BBC iPlayer outside of the UK using BIND and sniproxy[n1].

# Instructions
These instructions are based on a standard Ubuntu Docker image provided by Digital Ocean, but should work on any Linux distubution with Docker pre-installed.

1. Head over to Digital Ocean https://www.digitalocean.com/?refcode=937b01397c94 to create a Docker image
2. Create a Droplet using Docker 1.5.0 on Ubuntu 14.04 (find in under Applications images)
3. Make sure you create the Droplet in the UK data center (i.e. London).
3. SSH to your Droplet
4. cd /opt && git clone https://github.com/ab77/iplayer-proxy.git && cd iplayer-proxy && ./build.sh
5. Point your DNS at the Droplet IP to watch content avialable on BBC iPlayer regardless of which country you are in.
6. Enjoy!

-- ab1

[n1] https://github.com/dlundquist/sniproxy by Dustin Lundquist <dustin@null-ptr.net>
