# Redis
In-memory Data Structure Store for Open DevOps Pipeline

Redis is an advanced key-value cache and store. It is often referred to as a data structure server since keys can contain strings, hashes, lists, sets, sorted sets, bitmaps and hyperloglogs.

# TLDR
docker run --name devops-redis open-devops/redis

# Docker Compose
devops-redis:
  image: open-devops/redis
  
# Get this image
docker pull open-devops/redis



