package(default_visibility = ["//visibility:public"])

load("@numpy_test_requirements//:requirements.bzl", "requirement")
load("@rules_python//python:defs.bzl", "py_binary")

py_binary(
    name = "main",
    srcs = ["main.py"],
    deps = [
        requirement ("websockets"),
        requirement ("confluent-kafka"),
        requirement ("et-xmlfile"),
        requirement ("jdcal"),
        requirement ("numpy"),
        requirement ("openpyxl"),
        requirement ("pandas"),
        requirement ("python-dateutil"),
        requirement ("pytz"),
        requirement ("scikit-learn"),
        requirement ("scipy"),
        requirement ("six"),
        requirement ("azure-common"),
        requirement ("azure-storage-common"),
        requirement ("azure-storage-blob"),
        requirement ("tzlocal"),
        requirement ("applicationinsights"),
        requirement ("setuptools"),
        requirement ("joblib"),
        requirement ("cryptography"),
        requirement ("msrest"),
        requirement ("azure-core"),
        requirement ("requests"),
        requirement ("idna"),
        requirement ("asn1crypto"),
        requirement ("cffi"),
        requirement ("isodate"),
        requirement ("certifi"),
        requirement ("requests-oauthlib"),
        requirement ("chardet"),
        requirement ("urllib3"),
        requirement ("pycparser"),
        requirement ("oauthlib"),
    ],
)