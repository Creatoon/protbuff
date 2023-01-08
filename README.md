### Example of how to create protbuff files and manipulate (serialize and deserialize) them.

Protocol Buffers are a messaging format that forces the data structure to adhere to a specific schema. Because their interchangeable binary file takes up much less memory than JSON, it can reduce the number of times data is round-tripped over TCP and, if HTTP/2 is being used, it will also benefit from compression. It is also linguistically neutral.

### Usage

1) Generate .ts class files by compiling .proto files contained in src/
```sh
$ npm run ts:proto
```

2) Then run dist/index.js file to log the data generated using .proto file.
```
$ npm start
```

3) For any help, use the repo mentioned below
https://github.com/timostamm/protobuf-ts
