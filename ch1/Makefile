.DEFAULT_GOAL := build

.PHONY:fmt build
fmt:
	go fmt ./...
vet: fmt
	go vet ./...
build: vet
	go build