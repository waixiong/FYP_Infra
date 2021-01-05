build with 

[![](https://www.vectorlogo.zone/logos/traefikio/traefikio-ar21.svg)](https://traefik.io/traefik/)


# FYP Infrastructure Setup
The infrastructure is for my Final Year Project (FYP), utilizing Traefik Reverse Proxy for connecting multiple container (docker) services. The proxy will bring the request to its destination based on incoming subdomain, multiple project/s is/are serving through the proxy, currently 5 type of urls will redirect to my FYP related services.

- `5n.getitqec.com`: database
- `imagechat.getitqec.com/api/user/`: user_service
- `imagechat.getitqec.com/api/chat/`: chat_service
- `imagechat.getitqec.com/api/file/`: file_service
- `imagechat.getitqec.com/api/notification/`: notification_service


The infrastructure will be down after `07 FEB 2021`