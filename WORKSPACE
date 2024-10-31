# ./WORKSPACE

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Downloads and extracts a compressed archived file from the \
specified URL and creates a new repository rule with the given name.
http_archive(
    name = "rules_rust",

    # Specifies the SHA-256 hash of the tar file. This is used to \
    verify the integrity of the downloaded tar file.
    sha256 = "aaaa4b9591a5dad8d8907ae2dbe6e0eb49e6314946ce4c7149241648e56a1277",

    # Specifies the URL of a compressed archived file to download.
    urls = ["https://github.com/bazelbuild/rules_rust/releases/download/0.16.1/rules_rust-v0.16.1.tar.gz"],
)
