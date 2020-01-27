---
title: Git
author: vwkd
index: 1
tags:
---

## Introduction

- Distributed version control system
- Most efficient system, quasi standard
- Strange syntax is pulled straight out of Linus Torvalds' head
- History is represented as DAG



## Idea

- Version history for each file
- Enabling parallel work on same file



## Terminology

- repository: data store, includes complete history and metadata (? .git or working directory)
- commit: snapshot of entire repository at specific moment in time
- branch: fork in history, not own working directory, just seems like separate working directory, staging area, and project history (?)
- merge: combining two branches into one
- clone: a local copy of a repository
- fork: a copy of a repository from a different user (?)
- stash: temporarily shelves, when not ready to commit, like drafts, only local to own repository not pushed, under the hood are just commits
- checkout: setting up working directory from stage or repository (?)