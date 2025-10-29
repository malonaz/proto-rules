subinclude("//build_defs/sdk")

protoc_plugins(
    name = "proto_languages",
    build_defs = CONFIG.PROTO.DEFINITIONS,
    type = "proto_language",
)

protoc_plugins(
    name = "grpc_languages",
    build_defs = CONFIG.PROTO.DEFINITIONS,
    type = "grpc_language",
)


protoc_plugins(
    name = "grpc_gateway_languages",
    build_defs = CONFIG.PROTO.DEFINITIONS,
    type = "grpc_gateway_language",
)

filegroup(
    name = "proto",
    srcs = ["proto.build_defs"],
    visibility = ["PUBLIC"],
)
