<p align="center">
	<a href="https://pypi.python.org/pypi/mkdocs-material" rel="nofollow">
		<img src="https://img.shields.io/pypi/v/mkdocs-material.svg" alt="PyPI">
	</a>
	<a href="https://github.com/vuejs/vue">
		<img src="https://travis-ci.com/TwoDragonLake/tdl-saas-archive.svg?branch=master" alt="docs">
	</a>
	<a href="https://github.com/BladeCode/Material-Docs/master/LICENSE">
		<img src="https://img.shields.io/crates/l/rustc-serialize.svg" alt="license">
	</a>
</p>

[TwoDragonLake](https://github.com/TwoDragonLake) organization official project docs archive

# Introduction
Document summary,use mkdocs build
* [Preview](https://twodragonlake.github.io/tdl-saas-archive)
* [Mkdocs](http://www.mkdocs.org)
* [Theme](https://squidfunk.github.io/mkdocs-material)

## Project Branch Structure

```
tdl-saas-archive
    ├── gh-pages      	# automatic web source code
    └── master			# source code (edit branch)
```

# Preparation

## Installing Python
``` bash
python --version
Python 3.7.2
pip --version
pip 18.1
```
>MkDocs supports Python versions 2.7, 3.3, 3.4, 3.5 and pypy.

## Installing MkDocs

``` bash
pip install mkdocs
```

## Installing Theme

``` bash
pip install mkdocs-material
```

## Contribution

``` bash
# Get code
git clone https://github.com/TwoDragonLake/tdl-saas-archive.git
cd tdl-saas-archive
# run preview
mkdocs serve
# new docs (create a new file in the corresponding directory)，eg：new-docs.md
# add docs index (Page tree)
vim mkdocs.yml
# commit
git commit -m "eg:specific contents"
# push
git push
```

# Appendix
* [about manual deployment](https://github.com/davisp/ghp-import)
* [Automatically build related](https://docs.flc.io/more/github-travis-mkdocs-document)
* [Automatically build related](http://blog.agenric.cn/2017/12/10/Static-website-automation-build)

# License
© TwoDragonLake, 2018. Licensed under an [Apache-2](https://github.com/TwoDragonLake/tdl-saas-archive/blob/master/LICENSE) license.