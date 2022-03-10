
## Learning gRPC
@see [https://github.com/grpc/grpc-java](https://github.com/grpc/grpc-java)

@see [https://grpc.io/docs/languages/java/quickstart/](https://grpc.io/docs/languages/java/quickstart/)

- 本模块代码是拷贝自官方样例：https://github.com/grpc/grpc-java/tree/v1.45.0/examples/src/main/java/io/grpc/examples/helloworld

- 若本模块遇到类不存在的报红，请执行 `mvn clean compile` 生成 grpc 相关类。
```shell
mvn clean compile
```

执行后编译后请查看 target/generated-sources/protobuf，你将看到两个目录
- target/generated-sources/protobuf/java 为 com.google.protobuf:protoc 生成的模型
- target/generated-sources/protobuf/grpc-java 为 io.grpc:protoc-gen-grpc-java 自定义生成的 Grpc Stub 和 ImplBase
