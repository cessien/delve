load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

http_archive(
    name = "io_bazel_rules_go",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/rules_go/releases/download/v0.22.2/rules_go-v0.22.2.tar.gz",
        "https://github.com/bazelbuild/rules_go/releases/download/v0.22.2/rules_go-v0.22.2.tar.gz",
    ],
    sha256 = "142dd33e38b563605f0d20e89d9ef9eda0fc3cb539a14be1bdb1350de2eda659",
)

http_archive(
    name = "bazel_gazelle",
    urls = [
        "https://storage.googleapis.com/bazel-mirror/github.com/bazelbuild/bazel-gazelle/releases/download/v0.20.0/bazel-gazelle-v0.20.0.tar.gz",
        "https://github.com/bazelbuild/bazel-gazelle/releases/download/v0.20.0/bazel-gazelle-v0.20.0.tar.gz",
    ],
    sha256 = "d8c45ee70ec39a57e7a05e5027c32b1576cc7f16d9dd37135b0eddde45cf1b10",
)

load("@io_bazel_rules_go//go:deps.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains(
    go_version = "1.14.1",
)

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "com_github_cosiner_argv",
    importpath = "github.com/cosiner/argv",
    sum = "h1:rIXlvz2IWiupMFlC45cZCXZFvKX/ExBcSLrDy2G0Lp8=",
    version = "v0.0.0-20170225145430-13bacc38a0a5",
)

go_repository(
    name = "com_github_cpuguy83_go_md2man",
    importpath = "github.com/cpuguy83/go-md2man",
    sum = "h1:DwoNytLphI8hzS2Af4D0dfaEaiSq2bN05mEm4R6vf8M=",
    version = "v1.0.8",
)

go_repository(
    name = "com_github_davecgh_go_spew",
    importpath = "github.com/davecgh/go-spew",
    sum = "h1:ZDRjVQ15GmhC3fiQ8ni8+OwkZQO4DARzQgrnXU1Liz8=",
    version = "v1.1.0",
)

go_repository(
    name = "com_github_fsnotify_fsnotify",
    importpath = "github.com/fsnotify/fsnotify",
    sum = "h1:IXs+QLmnXW2CcXuY+8Mzv/fWEsPGWxqefPtCP5CnV9I=",
    version = "v1.4.7",
)

go_repository(
    name = "com_github_golang_protobuf",
    importpath = "github.com/golang/protobuf",
    sum = "h1:P3YflyNX/ehuJFLhxviNdFxQPkGK5cDcApsge1SqnvM=",
    version = "v1.2.0",
)

go_repository(
    name = "com_github_hpcloud_tail",
    importpath = "github.com/hpcloud/tail",
    sum = "h1:nfCOvKYfkgYP8hkirhJocXT2+zOD8yUNjXaWfTlyFKI=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_inconshreveable_mousetrap",
    importpath = "github.com/inconshreveable/mousetrap",
    sum = "h1:Z8tu5sraLXCXIcARxBp/8cbvlwVa7Z1NHg9XEKhtSvM=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_kr_pretty",
    importpath = "github.com/kr/pretty",
    sum = "h1:L/CwN0zerZDmRFUapSPitk6f+Q3+0za1rQkzVuMiMFI=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_kr_pty",
    importpath = "github.com/kr/pty",
    sum = "h1:VkoXIwSboBpnk99O/KFauAEILuNHv5DVFKZMBN/gUgw=",
    version = "v1.1.1",
)

go_repository(
    name = "com_github_kr_text",
    importpath = "github.com/kr/text",
    sum = "h1:45sCR5RtlFHMR4UwH9sdQ5TC8v0qDQCHnXt+kaKSTVE=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_mattn_go_colorable",
    importpath = "github.com/mattn/go-colorable",
    sum = "h1:isR/L+BIZ+rqODWYR/f526ygrBMGKZYFhaaFRDGvuZ8=",
    version = "v0.0.0-20170327083344-ded68f7a9561",
)

go_repository(
    name = "com_github_mattn_go_isatty",
    importpath = "github.com/mattn/go-isatty",
    sum = "h1:ns/ykhmWi7G9O+8a448SecJU3nSMBXJfqQkl0upE1jI=",
    version = "v0.0.3",
)

go_repository(
    name = "com_github_onsi_ginkgo",
    importpath = "github.com/onsi/ginkgo",
    sum = "h1:VkHVNpR4iVnU8XQR6DBm8BqYjN7CRzw+xKUbVVbbW9w=",
    version = "v1.8.0",
)

go_repository(
    name = "com_github_onsi_gomega",
    importpath = "github.com/onsi/gomega",
    sum = "h1:izbySO9zDPmjJ8rDjLvkA2zJHIo+HkYXHnf7eN7SSyo=",
    version = "v1.5.0",
)

go_repository(
    name = "com_github_peterh_liner",
    importpath = "github.com/peterh/liner",
    sum = "h1:8uaXtUkxiy+T/zdLWuxa/PG4so0TPZDZfafFNNSaptE=",
    version = "v0.0.0-20170317030525-88609521dc4b",
)

go_repository(
    name = "com_github_pkg_profile",
    importpath = "github.com/pkg/profile",
    sum = "h1:wBza4Dlm/NCQF572oSGNZ69flNFxlwIHjtwS6oy3Rvw=",
    version = "v0.0.0-20170413231811-06b906832ed0",
)

go_repository(
    name = "com_github_pmezard_go_difflib",
    importpath = "github.com/pmezard/go-difflib",
    sum = "h1:4DBwDE0NGyQoBHbLQYPwSUPoCMWR5BEzIk/f1lZbAQM=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_russross_blackfriday",
    importpath = "github.com/russross/blackfriday",
    sum = "h1:g9ZlAHmkc/h5So+OjNCkZWh+FjuKEOOOoyRkqlGA8+c=",
    version = "v0.0.0-20180428102519-11635eb403ff",
)

go_repository(
    name = "com_github_sirupsen_logrus",
    importpath = "github.com/sirupsen/logrus",
    sum = "h1:3AJZYTzw3gm3TNTt30x0CCKD7GOn2sdd50Hn35fQkGY=",
    version = "v0.0.0-20180523074243-ea8897e79973",
)

go_repository(
    name = "com_github_spf13_cobra",
    importpath = "github.com/spf13/cobra",
    sum = "h1:eRfW1vRS4th8IX2iQeyqQ8cOUNOySvAYJ0IUvTXGoYA=",
    version = "v0.0.0-20170417170307-b6cb39589372",
)

go_repository(
    name = "com_github_spf13_pflag",
    importpath = "github.com/spf13/pflag",
    sum = "h1:7bozMfSdo41n2NOc0GsVTTVUiA+Ncaj6pXNpm4UHKys=",
    version = "v0.0.0-20170417173400-9e4c21054fa1",
)

go_repository(
    name = "com_github_stretchr_objx",
    importpath = "github.com/stretchr/objx",
    sum = "h1:4G4v2dO3VZwixGIRoQ5Lfboy6nUhCyYzaqnIAPPhYs4=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_stretchr_testify",
    importpath = "github.com/stretchr/testify",
    sum = "h1:TivCn/peBQ7UY8ooIcPgZFpTNSz0Q2U6UrFlUfqbe0Q=",
    version = "v1.3.0",
)

go_repository(
    name = "in_gopkg_airbrake_gobrake_v2",
    importpath = "gopkg.in/airbrake/gobrake.v2",
    sum = "h1:7z2uVWwn7oVeeugY1DtlPAy5H+KYgB1KeKTnqjNatLo=",
    version = "v2.0.9",
)

go_repository(
    name = "in_gopkg_check_v1",
    importpath = "gopkg.in/check.v1",
    sum = "h1:qIbj1fsPNlZgppZ+VLlY7N33q108Sa+fhmuc+sWQYwY=",
    version = "v1.0.0-20180628173108-788fd7840127",
)

go_repository(
    name = "in_gopkg_fsnotify_v1",
    importpath = "gopkg.in/fsnotify.v1",
    sum = "h1:xOHLXZwVvI9hhs+cLKq5+I5onOuwQLhQwiu63xxlHs4=",
    version = "v1.4.7",
)

go_repository(
    name = "in_gopkg_gemnasium_logrus_airbrake_hook_v2",
    importpath = "gopkg.in/gemnasium/logrus-airbrake-hook.v2",
    sum = "h1:OAj3g0cR6Dx/R07QgQe8wkA9RNjB2u4i700xBkIT4e0=",
    version = "v2.1.2",
)

go_repository(
    name = "in_gopkg_tomb_v1",
    importpath = "gopkg.in/tomb.v1",
    sum = "h1:uRGJdciOHaEIrze2W8Q3AKkepLTh2hOroT7a+7czfdQ=",
    version = "v1.0.0-20141024135613-dd632973f1e7",
)

go_repository(
    name = "in_gopkg_yaml_v2",
    importpath = "gopkg.in/yaml.v2",
    sum = "h1:mUhvW9EsL+naU5Q3cakzfE91YhliOondGd6ZrsDBHQE=",
    version = "v2.2.1",
)

go_repository(
    name = "io_rsc_pdf",
    importpath = "rsc.io/pdf",
    sum = "h1:k1MczvYDUvJBe93bYd7wrZLLUEcLZAuF824/I4e5Xr4=",
    version = "v0.1.1",
)

go_repository(
    name = "net_starlark_go",
    importpath = "go.starlark.net",
    sum = "h1:lkYv5AKwvvduv5XWP6szk/bvvgO6aDeUujhZQXIFTes=",
    version = "v0.0.0-20190702223751-32f345186213",
)

go_repository(
    name = "org_golang_x_arch",
    importpath = "golang.org/x/arch",
    sum = "h1:QlVATYS7JBoZMVaf+cNjb90WD/beKVHnIxFKT4QaHVI=",
    version = "v0.0.0-20190927153633-4e8777c89be4",
)

go_repository(
    name = "org_golang_x_crypto",
    importpath = "golang.org/x/crypto",
    sum = "h1:VklqNMn3ovrHsnt90PveolxSbWFaJdECFbxSq0Mqo2M=",
    version = "v0.0.0-20190308221718-c2843e01d9a2",
)

go_repository(
    name = "org_golang_x_net",
    importpath = "golang.org/x/net",
    sum = "h1:R/3boaszxrf1GEUWTVDzSKVwLmSJpwZ1yqXm8j0v2QI=",
    version = "v0.0.0-20190620200207-3b0461eec859",
)

go_repository(
    name = "org_golang_x_sync",
    importpath = "golang.org/x/sync",
    sum = "h1:8gQV6CLnAEikrhgkHFbMAEhagSSnXWGV915qUMm9mrU=",
    version = "v0.0.0-20190423024810-112230192c58",
)

go_repository(
    name = "org_golang_x_sys",
    importpath = "golang.org/x/sys",
    sum = "h1:fgwFCsaw9buMuxNd6+DQfAuSFqbNiQZpcgJQAgJsK6k=",
    version = "v0.0.0-20190626221950-04f50cda93cb",
)

go_repository(
    name = "org_golang_x_text",
    importpath = "golang.org/x/text",
    sum = "h1:g61tztE5qeGQ89tm6NTjjM9VPIm088od1l6aSorWRWg=",
    version = "v0.3.0",
)

go_repository(
    name = "org_golang_x_tools",
    importpath = "golang.org/x/tools",
    sum = "h1:3MlESg/jvTr87F4ttA/q4B+uhe/q6qleC9/DP+IwQmY=",
    version = "v0.0.0-20191127201027-ecd32218bd7f",
)

go_repository(
    name = "org_golang_x_xerrors",
    importpath = "golang.org/x/xerrors",
    sum = "h1:9zdDQZ7Thm29KFXgAX/+yaf3eVbP7djjWp/dXAppNCc=",
    version = "v0.0.0-20190717185122-a985d3407aa7",
)
