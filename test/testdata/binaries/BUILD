package(default_visibility = ["//visibility:public"])

licenses(["notice"])

apple_binary(
    name = "empty_dylib",
    srcs = ["@bazel_tools//tools/objc:dummy.c"],
    binary_type = "dylib",
    platform_type = "ios",
)

apple_static_library(
    name = "empty_staticlib",
    srcs = ["@bazel_tools//tools/objc:dummy.c"],
    platform_type = "ios",
)
