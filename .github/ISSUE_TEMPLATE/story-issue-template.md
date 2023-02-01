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
- user should be able to run workflow X from UI
- enable workflow Y, Z from CLI

## Assumptions
* Support only Python Runtime
* Focus on DVC experiments only
* Deployment environments don't change often and can be picked up from shared configuration

## Open Questions
- How should access control work for shared artifacts (workflow X)
- Python runtime assumption - is it really valid? in light of <...>

## General Approach
Invocation example:
```shell
$ mapper-run task.tar.gz --ray-cluster <ip>:<port>
```

## Timeline

- end of week (Feb 3) for prototype with workflows X, Y
- Feb 15 - MVP in production
- Low priority followups can be done later

## Steps

### Must have (p1)
- [x] step 1
- [x] step 2
  - list of objects
  - output format

### Optional / followup (p2)
- [x] ⌛ step 3 wip
- [ ] step 4
