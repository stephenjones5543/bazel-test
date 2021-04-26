workspace (name = "numpy_test")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")


rules_python_version = "0ab06a2d6cc5abca83d9c8a21d65630b773a079b"

http_archive(
    name = "rules_python",
    #sha256 = "5be9610a959772697f57ec66bb58c8132970686ed7fb0f1cf81b22ddf12f5368",
    strip_prefix = "rules_python-{}".format(rules_python_version),
    url = "https://github.com/bazelbuild/rules_python/archive/{}.zip".format(rules_python_version),
)


load("@rules_python//python:pip.bzl", "pip_install")
pip_install(
    name = "numpy_test_requirements",
    requirements = "//main:requirements.txt",
)