# GRPC demo

 - git clone git@github.com:grpc-demo-hybrid/demo_server_go.git
 - cd demo_server_go/
 - git submodule init
 - git submodule update
 - protoc --go_out=plugins=grpc:. demo_proto/*.proto
 - go build