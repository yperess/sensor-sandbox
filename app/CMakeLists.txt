# Copyright (c) 2024 Google LLC
# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})

project(sensor-sandbox LANGUAGES C CXX)

target_sources(app PRIVATE src/main.cc)

