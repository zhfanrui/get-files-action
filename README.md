# get-files-action
---
```
name: get-files-tree-action
on: [push]

jobs:
  build:

    runs-on: ubuntu-latest

    steps:
    - uses: zhfanrui/get-files-action@master
      with:
        accessToken: ${{ secrets.GITHUB_TOKEN }}
        
```
