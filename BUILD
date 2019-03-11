licenses(["notice"])

package(default_visibility = ["//visibility:public"])

cc_test(
    name = "tdigest_test",
    size = "small",
    srcs = [
        "tdigest_test.cpp",
    ],
    copts = [
        "-std=c++17",
    ],
    deps = [
        ":tdigest",
        "@com_github_google_glog//:glog",
        "@com_google_googletest//:gtest",
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
