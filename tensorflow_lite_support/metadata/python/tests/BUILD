package(
    default_visibility = [
        "//visibility:public",
    ],
    licenses = ["notice"],  # Apache 2.0
)

py_test(
    name = "metadata_test",
    srcs = ["metadata_test.py"],
    data = ["//tensorflow_lite_support/metadata/python/tests/testdata:test_files"],
    python_version = "PY3",
    srcs_version = "PY2AND3",
    deps = [
        # six dep,
        # tensorflow dep,
        "//tensorflow_lite_support/metadata:metadata_schema_py",
        "//tensorflow_lite_support/metadata:schema_py",
        "//tensorflow_lite_support/metadata/python:metadata",
        "@flatbuffers//:runtime_py",
    ],
)

py_test(
    name = "metadata_parser_test",
    srcs = ["metadata_parser_test.py"],
    python_version = "PY3",
    srcs_version = "PY2AND3",
    deps = [
        # tensorflow dep,
        "//tensorflow_lite_support/metadata/python:metadata",
    ],
)
