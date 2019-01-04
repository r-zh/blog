+++
title = "Git Commands in Usage"
date = 2018-12-16T19:20:56-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Git"]
categories = ["Tool"]

+++
## Overview
![git_structure.png](https://a.photo/images/2019/01/05/git_structure.png)

## Update website
Using [Hugo](https://gohugo.io/getting-started/) to set personal website has some issues about Git to attention. Source code and website code are independent.

| Category  | Source code      | Website Code            |
|-----------|------------------|-------------------------|
| Creation  | Manually         | Automatically           |
| File type | .md              | .html                   |
| Usage     | Edit the Content | Display the Information |
| Folder    | hugo root        | public                  |

Therefore, we need to develop the source code firstly, and push it to git. Then, refresh the public folder to update the blog website. The steps are as follows.

- Git push Blog source
- Create `public` folder
- Operate the following commands:

```
cd public
git clone https://github.com/:github_account/:git_repository ./
cd ..
hugo 
cd public
git add .
git commit -m 'update blog'
git push
```
