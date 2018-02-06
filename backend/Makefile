build: 
	GOOS=linux go build -o app
	docker build -t gcr.io/bgk-say/say .
	rm -f app

push:
	gcloud docker -- push gcr.io/bgk-say/say