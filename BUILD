load("@rules_pkg//:pkg.bzl", "pkg_zip")
load("@rules_pkg//pkg:mappings.bzl", "pkg_files")

pkg_zip(
    name = "graftorio2",
    srcs = [
        "control.lua",
        "events.lua",
        "info.json",
        "power.lua",
        "research.lua",
        "settings.lua",
        "thumbnail.png",
        "train.lua",
        "utils.lua",
        "yarm.lua",
        "//prometheus",
    ],
    out = "kleinpa-graftorio2_0.0.1.zip",
    package_dir = "graftorio2",
)
