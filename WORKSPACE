git_repository(
    name = "com_github_gflags_gflags",
    commit = "c6b937797c00a3bc736bf7ffcdc0d6a9117c2743",
    remote = "https://github.com/gflags/gflags.git",
)

bind(
    name = "gflags",
    actual = "@com_github_gflags_gflags//:gflags",
)

http_archive(
    name = "protobuf",
    url = "http://github.com/google/protobuf/archive/008b5a228b37c054f46ba478ccafa5e855cb16db.tar.gz",
    sha256 = "2737ad055eb8a9bc63ed068e32c4ea280b62d8236578cb4d4120eb5543f759ab",
    strip_prefix = "protobuf-008b5a228b37c054f46ba478ccafa5e855cb16db",
)

bind(
    name = "protobuf_clib",
    actual = "@protobuf//:protoc_lib",
)

bind(
    name = "protobuf_compiler",
    actual = "@protobuf//:protoc_lib",
)


new_http_archive(
    name = "swig",
    sha256 = "58a475dbbd4a4d7075e5fe86d4e54c9edde39847cdb96a3053d87cb64a23a453",
    url = "http://jaist.dl.sourceforge.net/project/swig/swig/swig-3.0.8/swig-3.0.8.tar.gz",
    strip_prefix = "swig-3.0.8",
    build_file = "third_party/swig.BUILD",
)

new_http_archive(
    name = "pcre",
    sha256 = "ccdf7e788769838f8285b3ee672ed573358202305ee361cfec7a4a4fb005bbc7",
    url = "http://ftp.exim.org/pub/pcre/pcre-8.39.tar.gz",
    strip_prefix = "pcre-8.39",
    build_file = "third_party/pcre.BUILD",
)