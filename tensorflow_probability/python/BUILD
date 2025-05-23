# Copyright 2018 The TensorFlow Probability Authors.
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
# ============================================================================
# Description:
#   TensorFlow Probability implements probabilistic and statistical
#   methods, including modeling and Bayesian inference. APIs here are
#   meant to evolve over time.

# Placeholder: py_library

licenses(["notice"])

package(
    # default_applicable_licenses
    default_visibility = [
        "//tensorflow_probability:__subpackages__",
    ],
)

py_library(
    name = "python",
    srcs = ["__init__.py"],
    visibility = ["//tensorflow_probability:__pkg__"],
    deps = [
        ":version",
        # distutils dep,
        "//tensorflow_probability/python/bijectors",
        "//tensorflow_probability/python/debugging",
        "//tensorflow_probability/python/distributions",
        "//tensorflow_probability/python/experimental",
        "//tensorflow_probability/python/glm",
        "//tensorflow_probability/python/internal",
        "//tensorflow_probability/python/internal:all_util",
        "//tensorflow_probability/python/internal:lazy_loader",
        "//tensorflow_probability/python/layers",
        "//tensorflow_probability/python/math",
        "//tensorflow_probability/python/mcmc",
        "//tensorflow_probability/python/monte_carlo",
        "//tensorflow_probability/python/optimizer",
        "//tensorflow_probability/python/random",
        "//tensorflow_probability/python/stats",
        "//tensorflow_probability/python/sts",
        "//tensorflow_probability/python/util",
        "//tensorflow_probability/python/vi",
    ],
)

py_library(
    name = "version",
    srcs = ["version.py"],
)
