# Embeddings for code comprehension.

py_library(
    name = "inst2vec_preprocess",
    srcs = ["inst2vec_preprocess.py"],
    visibility = ["//visibility:public"],
    deps = [
        ":inst2vec_utils",
        "//third_party/py/ncc:rgx_utils",
        "//third_party/py/networkx",
    ],
)

py_library(
    name = "inst2vec_utils",
    srcs = ["inst2vec_utils.py"],
)
