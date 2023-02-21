---
title: sample
categories: |
  dataframe
version: 0.75.0
dataframe: |
  Create sample dataframe
usage: |
  Create sample dataframe
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> sample ```

## Examples

Sample rows from dataframe
```shell
> [[a b]; [1 2] [3 4]] | into df | sample -n 1
```

Shows sample row using fraction and replace
```shell
> [[a b]; [1 2] [3 4] [5 6]] | into df | sample -f 0.5 -e
```