java_thrift_library(
    name = "thrift-scala",
    sources = rglobs("*.thrift"),
    compiler = "scrooge",
    language = "scala",
    provides = artifact(
        org = "com.twitter",
        name = "finagle-integration-thrift-scala",
        repo = artifactory,
    ),
)
