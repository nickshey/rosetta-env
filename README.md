# Making Rosetta Environment

## Clone Repo
```
git clone https://github.com/nickshey/rosetta-env.git
```

## Build Image
```
docker build -t rosetta .
```

## Enter Image
```
docker run -t rosetta
```

## Train ResNet50
```
docker-compose up -f docker-compose-train.yaml
```