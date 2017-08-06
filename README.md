version
=========

A simple library for Golang to embed the current code version, based
on looking of the current Git commit hash, branch, and tag.

The Makefile does the heavy lifting, and records its observation
in the `gitcommit.go` file.

Hence projects using this library are expected to be built with `make`.
