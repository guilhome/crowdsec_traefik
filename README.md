# crowdsec_traefik

https://technotim.live/posts/crowdsec-traefik/

docker exec crowdsec cscli metrics

docker exec crowdsec cscli collections install crowdsecurity/traefik

docker exec crowdsec cscli hub update && docker exec crowdsec cscli hub upgrade

docker exec crowdsec cscli decisions list

docker exec crowdsec cscli bouncers add bouncer-traefik

docker exec crowdsec cscli decisions add --ip x.x.x.x

docker exec crowdsec cscli decisions delete --ip x.x.x.x