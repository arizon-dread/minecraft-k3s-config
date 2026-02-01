# Minecraft server

## Java on k3s on raspberry pi 4

This is a setup for running a Minecraft: Java Edition server on top of k3s/kubernetes on rpi4.

## Bedrock on microk8s on VPS

The minecraft-bedrock-vps folder contains deploy, svc and pvc for running it on my VPS.

This folder also contains a maintenance deploy that is used to configure the server, mounting the same PVC on `/data` so the server.properties file can be examined and edited with text editors.
