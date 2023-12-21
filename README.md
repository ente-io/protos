# protos


## Dart Bindings

### Setup

```bash
brew install protobuf
dart pub global activate protoc_plugin
export PATH="$PATH":"$HOME/.pub-cache/bin"
```

```shell
protoc --proto_path=. --dart_out=grpc:dart/ protos/**/*.proto  
```