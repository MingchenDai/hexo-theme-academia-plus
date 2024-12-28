# hexo-theme-academia-plus

hexo-theme-academia-plus is an enhanced version of the Academia theme, designed for academic websites powered by Hexo. It builds upon [Academia](https://github.com/PhosphorW/hexo-theme-academia), which was originally adapted from Jekyll's academicpages, offering additional features and improvements.

## Introduction

This repository includes minor updates to the Academia theme. For detailed information and the original features, refer to the [Academia repository](https://github.com/PhosphorW/hexo-theme-academia).

## What's New

- $\LaTeX$ is now supported. To enable $\LaTeX$ rendering, update your` _config.yml` file with the following configurations:

  ```yaml
  math:
  engine: 'mathjax'
    mathjax:
    src: https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML 

  mathjax:
    enable: true
    cdn: https://cdn.jsdelivr.net/npm/mathjax@2.7.8/MathJax.js?config=TeX-AMS-MML_HTMLorMML

  ```

  You should also add `mathjax: true` in the introduction part of each `.md` file with $\LaTeX$ formulas.

- Two new pages: `Explorations` and `Posts` are added to better organize content. You can add `section: Explorations` or `section: Posts` in the introduction part of each `.md` file to make file to be automatically sorted by an order of time and title.
- Posts now display their update time and parent page. To enable this feature, you must define the type attribute in the front matter of each `.md` file ( `Page` or `Post` ).
- You can now add tags to your posts! Tags are displayed just before your content to improve organization and navigation.

## To-do list

- [ ] Add a category into the sidebar.
- [x] Complete tegs.

## Acknowledgements

Great thanks to [PhosphorW](https://github.com/PhosphorW). Your academic theme is excellent.