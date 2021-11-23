load("@io_bazel_rules_scala//scala:scala.bzl", "scala_binary")

scala_binary (
    name = "BazelApp",
    srcs = glob(["scala/**/*.scala"]),
    main_class = "example.App",
    deps = [
      "@maven//:org_mongodb_mongo_java_driver",
    ],
)
