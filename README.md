# Local Wordpress Development with Docker

This project lets you easily spin up a local Wordpress design environment.

All you have to do is execute `docker-compose u --build`

Additionally, it lets you expose your work to the internet with ngrok :D

## Quickstart

1. Copy `docker-compose.yaml.sample` to `docker-compose.yaml`
2. Replace `NGROK_KEY` with your NGROK Authentication Token
3. Start your Compose project `docker-compose u --build`

## NGROK Integration References

https://medium.com/oracledevs/expose-docker-container-services-on-the-internet-using-the-ngrok-docker-image-3f1ea0f9c47a
https://github.com/wernight/docker-ngrok/issues/65
https://dashboard.ngrok.com/get-started/setup
https://docs.docker.com/compose/compose-file/

Couldn't make it work with the official image :/
https://hub.docker.com/r/ngrok/ngrok/
