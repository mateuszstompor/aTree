## Purpose
In order to create animations hierarchy of bones and parts of a model needs to be preserved.
It can be achived using directed acyclic graphs, but trees have many advantages, one of which is their simplicity.
Class enables user to create hierarchical tree, modify its structure and provide iterator which can notify whenever it changes level during iteration. Why is it important? This feature provides a convenient way to concatenate tranformations. 

## Where can I find the main class?
In file named "tree.hpp"

## How many files I need to include?
Only one

## How to compile it?
There is no need of compilation. It is a header only, one class lib.

## Can I trust it?
Yes, whole project is tested and works correctly.

## Requirements
In order to use class you need to use of listed compilers to build your project.
<ul>
<li>GCC, version 8.1</li>
<li>clang, version 6.0</li>
</ul>

## Build status
[![Build Status](https://www.travis-ci.org/mateuszstompor/tree.svg?branch=master)](https://www.travis-ci.org/mateuszstompor/tree)
