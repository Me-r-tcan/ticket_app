# start dev

skaffold dev

kubectl create secret generic jwt-secret --from-literal=JWT_KEY={{SECRET_KEY}}

# Site

https://ticketing.dev/

# nats port forward

kubectl port-forward nats-depl-67b76b98c6-n4xjs 4222:4222
