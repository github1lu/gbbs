cc_library(
  name = "DegeneracyOrder",
  hdrs = ["DegeneracyOrder.h"],
  deps = [
  "//ligra:bucket",
  "//ligra:edge_map_reduce",
  "//ligra:ligra",
  "//ligra/pbbslib:dyn_arr",
  "//pbbslib:integer_sort",
  "//benchmarks/ApproximateDensestSubgraph/GreedyCharikar:DensestSubgraph",
  "//benchmarks/ApproximateDensestSubgraph/ApproxPeelingBKV12:DensestSubgraph",
  ]
)

cc_binary(
  name = "DegeneracyOrder_main",
  srcs = ["DegeneracyOrder.cc"],
  deps = [":DegeneracyOrder"]
)

package(
  default_visibility = ["//visibility:public"],
)
