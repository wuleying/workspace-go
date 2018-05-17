package(licenses = ["notice"])  # Apache 2.0

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "log",
    srcs = [
        "llog.go",
    ],
    importpath = "github.com/wuleying/workspace-go/pkg/log",
    visibility = [
        "//visibility:public",
    ],
    deps = ["//pkg/linewriter"],
)