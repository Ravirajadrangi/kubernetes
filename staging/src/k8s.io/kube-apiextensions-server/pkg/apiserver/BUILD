package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "apiserver.go",
        "customresource_discovery.go",
        "customresource_discovery_controller.go",
        "customresource_handler.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//vendor/github.com/golang/glog:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/meta:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apimachinery/announced:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apimachinery/registered:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/labels:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer/json:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/version:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/admission:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/discovery:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/handlers:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/request:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/registry/generic:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/registry/generic/registry:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/registry/rest:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/server:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/storage/storagebackend:go_default_library",
        "//vendor/k8s.io/client-go/discovery:go_default_library",
        "//vendor/k8s.io/client-go/tools/cache:go_default_library",
        "//vendor/k8s.io/client-go/util/workqueue:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/apis/apiextensions:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/apis/apiextensions/install:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/apis/apiextensions/v1alpha1:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/clientset/clientset:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/clientset/internalclientset:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/externalversions:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/internalversion/apiextensions/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/listers/apiextensions/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/registry/customresource:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/registry/customresourcestorage:go_default_library",
    ],
)
