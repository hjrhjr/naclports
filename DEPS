deps = {
  "src/third_party/libapps":
    "https://chromium.googlesource.com/apps/libapps.git@0bec09b",
  "src/third_party/mock":
    "https://github.com/sbc100/mock.git@6206f33",
  "src/third_party/zip.js":
    "git://github.com/gildas-lormeau/zip.js@4c93974"
}

deps_os = {
  "win": {
    "src/third_party/cygwin":
      "http://src.chromium.org/svn/trunk/deps/third_party/cygwin@11984",
    "src/native_client/build":
      "http://src.chromium.org/native_client/trunk/src/native_client/build"
  },
}

hooks = [
  {
    "name": "clean_pyc",
    "pattern": ".",
    "action": [
        "python", "src/build_tools/clean_pyc.py", "src/build_tools", "src/lib"
    ],
  },
]
