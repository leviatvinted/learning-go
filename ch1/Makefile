.DEFAULT_GOAL := build

.PHONY:fmt vet build clean
fmt:
		go fmt ./...

vet: fmt
		go vet ./...

build: vet
		go build -o hello_world

# Standalone command
clean:
		rm -f hello_world