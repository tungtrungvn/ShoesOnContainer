﻿# ShoesOnContainer

build and run:

docker-compose build
docker-compose up basket.data mssqlserver rabbitmq
docker-compose up order tokenserver cart catalog webmvc

Note: docker must be able to share drive C:, VPN may interfere with accessing http://10.0.75.1 (openId uses docker NAT)
