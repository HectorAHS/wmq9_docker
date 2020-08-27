# wmq9_docker
Build a WebSphere MQ v9 docker container

	docker build -t hhuaranga/wmq9 .
	docker login
	docker push hhuaranga/wmq9

# Nota
Solo el yaml del despliegue es necesario, los ingress del LB se crean directamente desde Rancher, de momento