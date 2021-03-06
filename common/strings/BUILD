# This package contains functions for dealing specifically with strings.

licenses(["notice"])

package(
    default_visibility = [
        "//:__subpackages__",
    ],
)

cc_library(
    name = "compare",
    hdrs = ["compare.h"],
    deps = [
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "compare_test",
    srcs = ["compare_test.cc"],
    deps = [
        ":compare",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "comment_utils",
    srcs = ["comment_utils.cc"],
    hdrs = ["comment_utils.h"],
    deps = [
        "//common/util:logging",
        "//common/util:range",
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "comment_utils_test",
    srcs = ["comment_utils_test.cc"],
    deps = [
        ":comment_utils",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "naming_utils",
    srcs = ["naming_utils.cc"],
    hdrs = ["naming_utils.h"],
    deps = ["@com_google_absl//absl/strings"],
)

cc_test(
    name = "naming_utils_test",
    srcs = ["naming_utils_test.cc"],
    deps = [
        ":naming_utils",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "position",
    srcs = ["position.cc"],
    hdrs = ["position.h"],
    deps = [
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "position_test",
    srcs = ["position_test.cc"],
    deps = [
        ":position",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "range",
    srcs = ["range.cc"],
    hdrs = ["range.h"],
    deps = [
        "//common/util:logging",
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "range_test",
    srcs = ["range_test.cc"],
    deps = [
        ":range",
        "//common/util:range",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "rebase",
    srcs = ["rebase.cc"],
    hdrs = ["rebase.h"],
    deps = [
        "//common/util:logging",
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "rebase_test",
    srcs = ["rebase_test.cc"],
    deps = [
        ":rebase",
        "//common/util:range",
        "@com_google_absl//absl/base:core_headers",
        "@com_google_absl//absl/strings",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "utf8",
    hdrs = ["utf8.h"],
    deps = [
        "@com_google_absl//absl/strings",
    ],
)

cc_test(
    name = "utf8_test",
    srcs = ["utf8_test.cc"],
    deps = [
        ":utf8",
        "@com_google_absl//absl/strings",
        "@com_google_googletest//:gtest_main",
    ],
)
