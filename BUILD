cc_library(
    name = "modern-cpp-kafka-api",

    hdrs = glob(["include/kafka/*.h", "include/kafka/addons/*.h"]),

    includes = ["include"],

    linkopts = ["-lpthread", "-lrdkafka"],

    visibility = ["//visibility:public"],
)

