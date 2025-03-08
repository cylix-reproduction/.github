# Cylix's Reproduction of Papers
![status](https://img.shields.io/badge/status-work_in_progress-green?style=flat-square)
![build system](https://img.shields.io/badge/package_manager-uv-DE5FE9?style=flat-square)

This organization account contains repositories that is reproduced from papers. Generally, the repositories under this organization are forked, slightly modified or created from scratch to reproduce the results in papers.

> **Package Manager**
>
> Most of source code appeared in papers is provided in Python language. However, the repositories and/or their dependencies may not be well-organized using a `pyproject.toml`, as [PEP 518](https://peps.python.org/pep-0518/) specifies. Under this organization, repositories are guaranteed to be (re-)organized using `pyproject.toml` and the [uv](https://docs.astral.sh/uv/) package manager.

- [Created-from-scratch reproduction](#created-from-scratch-reproduction)

## Created-from-scratch reproduction
Repositories listed below are created from scratch, and does **NOT** guarantee 100% precise match with the results in original papers. However, they should reproduce the core principle to some extent.
| Referenced paper                                                                                  | Repository                                                                                   |
|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083) | [adversarial-training-demo](https://github.com/cylix-reproduction/adversarial-training-demo) |
