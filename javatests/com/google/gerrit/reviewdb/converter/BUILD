load("//tools/bzl:junit.bzl", "junit_tests")

junit_tests(
    name = "proto_converter_tests",
    srcs = glob(["*.java"]),
    deps = [
        "//java/com/google/gerrit/proto/testing",
        "//java/com/google/gerrit/reviewdb:server",
        "//lib:guava",
        "//lib:protobuf",
        "//lib/guice",
        "//lib/jgit/org.eclipse.jgit:jgit",
        "//lib/truth",
        "//lib/truth:truth-proto-extension",
        "//proto:entities_java_proto",
    ],
)
