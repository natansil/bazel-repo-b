package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_specs2_junit_test", "scala_binary")

scala_library(
    name="b1",
    srcs=[
        "B.scala",
        ],
    deps=[
        "@repo_a//:a2",
        ],

)

scala_library(
    name="b2",
    srcs=[
        "B.scala",
        ],
)
