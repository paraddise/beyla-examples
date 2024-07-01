otlp-up:
	docker compose -f docker-compose.yaml up -d --remove-orphans

otlp-stop:
	docker compose -f docker-compose.yaml stop

youtrack-up:
	docker compose -f youtrack/docker-compose.yaml up -d --remove-orphans

youtrack-stop:
	docker compose -f youtrack/docker-compose.yaml stop

akeneo-init:
	cd akeneo
	make
akeneo-up:
	docker compose -f akeneo/docker-compose.yml up -d --remove-orphans mysql httpd elasticsearch object-storage beyla-httpd beyla-elastic beyla-minio
akeneo-stop:
	docker compose -f akeneo/docker-compose.yml stop


