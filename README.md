https://ghcr.io

cho $PAT | docker login ghcr.io --username phanatic --password-stdin


docker tag app ghcr.io/phanatic/app:1.0.0

docker push ghcr.io/phanatic/app:1.0.0
