rules_scala_version="7b9b89b70bfd6935ccfc9886105471ba4b733fd1"

http_archive(
             name = "io_bazel_rules_scala",
             url = "https://github.com/bazelbuild/rules_scala/archive/%s.zip"%rules_scala_version,
             type = "zip",
             strip_prefix= "rules_scala-%s" % rules_scala_version
             )

repo_a_version="a6fa00116b9d139982e7b3128d1b311545055c5c"

http_archive(
             name = "repo_a",
             url = "https://github.com/natansil/bazel-repo-a/archive/%s.zip"%repo_a_version,
             type = "zip",
             strip_prefix= "bazel-repo-a-%s" % repo_a_version
             )

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()

load("@io_bazel_rules_scala//specs2:specs2_junit.bzl","specs2_junit_repositories")
specs2_junit_repositories()


