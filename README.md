### Example of how to create protbuff files and manipulate (serialize and deserialize) them.

Protocol Buffers are simply messaging format which forces the data structure to follow a particular schema whose interchangable binary file occupies very less memory than json, hence it can save extra roundtrips to chunkify data in tcp also if we are using HTTP/2, that small binary file will also get compressed hence more advantage of using this. It's also language neutral.

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
