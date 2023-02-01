---
name: Story Issue Template
about: Template for Story level issues (< 2 weeks)
title: 'Story: My Story'
labels: story
assignees: omesser

---

## Summary / Background
What do you want to achieve, why? business context
...

## Scope
- user can do X with Y
- enable workflow Z

## Assumptions
* Support only Python Runtime
* Focus on DVC experiments only
* Deployment environments don't change often and can be picked up from shared configuration

## General Approach
Invocation example:
```shell
$ mapper-run task.tar.gz --ray-cluster <ip>:<port>
```


## Steps
- [x] step 1
- [x] step 2
  - list of objects
  - output format
- [x] ⌛ step 3 wip
- [] step 4
