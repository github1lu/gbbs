cc_library(
  name = "SpanningForest",
  hdrs = ["SpanningForest.h"],
  deps = [
  "//ligra:ligra",
  "//benchmarks/SpanningForest:common",
  ]
)

cc_binary(
  name = "SpanningForest_main",
  srcs = ["SpanningForest.cc"],
  deps = [":SpanningForest"]
)

package(
  default_visibility = ["//visibility:public"],
)
