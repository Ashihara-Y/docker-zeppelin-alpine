# Apache Zeppelin instance compatible with Flink 1.3.2

	docker run yashihara/docker-zeppelin-alpine:latest
	docker run -v <path_to_notebooks_on_host>:/zeppelin/notebook -p 8080:8080 docker-zeppelin-alpine:latest

The Zeppelin UI can be reached on port `8080`.
