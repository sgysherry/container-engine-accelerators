TAG?=0.1.0
REGISTRY?=us-west1-docker.pkg.dev/yshangguan-gke-dev/sgy-test-image
IMAGE=xid-trigger

container:
	docker build --pull -t ${REGISTRY}/${IMAGE}:${TAG} .

push:
	docker push ${REGISTRY}/${IMAGE}:${TAG}