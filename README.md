``` bash
#go mod init github.com/username/repositoryname/backend
#go get github.com/gin-gonic/gin


mkdir** -p cmd/server \
internal/{config,domain,repository,service,transport/{http,grpc},utils} \
pkg \
migrations

mkdir -p lib/{models,services,screens,widgets}