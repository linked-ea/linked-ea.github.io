---
title: Home
layout: home
nav_order: 1
---

# Linking Enterprise Architecture Information


Just link your Enterprise Architecture model to public or private templates and other foundational models.
{: .fs-6 .fw-300 }

{: .warning }
> This website is under construction.

{: .important }
> This website documents experimental and proof-of-concept features which should not be utilized in production.


## Motivation

To some extent, every single architecture initiative that is based on an Enterprise Architecture model starts from scratch, and typically locked to an software tool or service. Through the selected tool, an architecture metamodel is defined (or adopted from standards like [Archimate®]), architecture domains are identified, template diagrams are developed, and architecture data to be used is identified, activities that become as time consuming as the architecture initiative itself, before the actual work starts.

It feels like a significant amount of effort even before the first architecture artifact is captured. The metaphor I to use is that "the construction of road that takes us to the to-be built facility is bigger than the facility itself".

As a result, business organizations developed a "traumatic disorder" in respect to architecture initiatives, perceiving the benefits being small than the effort and costs. Often enterprise architecture teams are assembled and disassembled due to their perceived cost/benefit, and organizations unknowingly (or accepting it) loose tacit and coded knowledge of their business, information and technnology architectures.




## Deliverables

To create and share:

* A technology standard to allow reference of architecture information resources across models
* Proof-of-concept reference implementations to validate the standard using Typescript[^1]
* Initial set of reference templates to collect feedback and validate the standard

## Benefits

## Primary Audience
* Enterprise Architects
* Solution Architects
* Business Architects


This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

## Contributions
While it's not necessary, we'd love to hear from you if you do use this template, and how we can improve it for future use!

## About the project

* linked-ea is &copy; 2024-{{ "now" | date: "%Y" }} by [Luis Pellicano](https://github.com/americanpelican)

----
## Licensing and Attributions
This project is licensed under the [MIT License]. In short summary, you are generally free to reuse or extend upon this code as you see fit, just include the original copy of the license.

* [ArchiMate® is a registered trademark of The Open Group]


[^1]: [Typescript](https://www.typescriptlang.org)

[MIT License]: https://en.wikipedia.org/wiki/MIT_License
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
[ArchiMate® is a registered trademark of The Open Group]: https://www.opengroup.org/archimate-forum/archimate-overview
[ArchiMate®]: https://www.opengroup.org/archimate-forum/archimate-overview
