load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library_internal")

licenses(["notice"])  # Apache 2

api_proto_library_internal(
    name = "redis_proxy",
    srcs = ["redis_proxy.proto"],
    deps = [
        "//envoy/api/v2/core:base",
    ],
)
