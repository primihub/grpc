# Copyright 2017 gRPC authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])

load("@rules_proto//proto:defs.bzl", "proto_library")
load("//bazel:grpc_build_system.bzl", "grpc_package", "grpc_proto_library")

grpc_package(
    name = "health",
    visibility = "public",
)

grpc_proto_library(
    name = "health_proto",
    srcs = ["health.proto"],
)

proto_library(
    name = "health_proto_descriptor",
    srcs = ["health.proto"],
)

filegroup(
    name = "health_proto_file",
    srcs = [
        "health.proto",
    ],
)
