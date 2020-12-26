# n8n + Kubernetes + Traefik

### Information

Software: https://n8n.io/

Docker Documentation: https://github.com/n8n-io/n8n/blob/master/docker/images/n8n/README.md

Made this software to sit on my k3s server - It has data persistence saved to /srv/n8n & also works with traefik's Let's Encrypt & reverse proxy through ingress.yaml which you can replace with your own. It uses the builtin database but can be motified with the above documentation. 
