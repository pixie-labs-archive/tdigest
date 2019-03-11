licenses(["notice"])
package(default_visibility = ["//visibility:public"])

cc_test(
    name = "tdigest_test",
    srcs = [
        "tdigest_test.cpp",
    ],
    size = "small",
    deps = [
        ":tdigest",
        "@com_google_googletest//:gtest",
        "@com_github_google_glog//:glog",
    ],
    copts = [
        "-std=c++17",
    ],
)

cc_library(
    name = "tdigest",
    srcs = [
    ],
    hdrs = [
        "tdigest.h",
    ],
    copts = [
        "-std=c++17",
    ],
)


