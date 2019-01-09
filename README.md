# ShoesOnContainer

build and run:

1. docker-compose build
2. docker-compose up basket.data mssqlserver rabbitmq
3. docker-compose up order tokenserver cart catalog webmvc

live demo: http://ec2-52-27-123-98.us-west-2.compute.amazonaws.com:5200
Note: docker must be able to share drive C:, VPN may interfere with accessing http://10.0.75.1 (openId uses docker NAT)
