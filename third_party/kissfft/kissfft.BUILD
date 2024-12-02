package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

exports_files(["COPYING"])

cc_library(
    name = "kiss_fftr_16",
    srcs = [
        "kiss_fft.c",
        "tools/kiss_fftr.c",
    ],
    hdrs = [
        "_kiss_fft_guts.h",
        "kiss_fft.h",
        "tools/kiss_fftr.h",
    ],
    copts = [
        "-DFIXED_POINT=16",
    ],
)
