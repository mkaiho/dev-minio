# dev-minio

## launch containers

```.sh
docker-compose up --build -d
```

## shutdown containers

```.sh
docker-compose down
```

## access local minio container using aws-cli

```.sh
docker exec -it awscli bash

aws --endpoint-url http://minio:9000 s3 <command>
```

## login minio on browser

- URL: <http://localhost:9000/login>
- Username: AKIAIOSFODNN7EXAMPLE
- Password: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
