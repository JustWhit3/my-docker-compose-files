<p align="center"><img src="https://github.com/JustWhit3/my-docker-compose-files/blob/main/img/logo.svg" height=220></p>

<h3 align="center">A collection of all my docker-compose files</h3>
<p align="center">
    <a href="LICENSE">
        <img title="MIT License" alt="license" src="https://img.shields.io/badge/license-MIT-informational?style=flat-square">
    </a>
	<img title="Repo size" alt="repo size" src="https://img.shields.io/github/repo-size/JustWhit3/my-docker-compose-files?color=red">
</p>

***

## Table of contents

- [Introduction](#introduction)
- [List of files](#list-of-files)
  - [cpp_compilers_testing](#cppcompilerstesting)

## Introduction

This repository contains all my docker-compose files. The only purpose for the existence of this repository is that I want to keep them safe in the same place and share with other for free.

## List of files

### [cpp_compilers_testing](https://github.com/JustWhit3/my-docker-compose-files/files/cpp_compilers_testing)

**Description**: this docker-compose file is used to test different C++ compilers (gcc, clang, etc...) and their different versions on the same file, without the needing of installing each version / compiler in your machine. With the same purpose you can use it also to test different C++ standards.

**Usage**: add new lines with other compilers or other compilers versions to the .yml file and then run the required compiler version on the example file [test.cpp](https://github.com/JustWhit3/my-docker-compose-files/files/cpp_compilers_testing/test.cpp).

**Example**: to run the test on gcc 11, enter the docker-compose file directory and do:

```Bash
sudo docker-compose run --rm build_gcc_11
```
