
---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
  - [**Best-of Generator**](https://github.com/best-of-lists/best-of-generator): Generates a ranked markdown list of awesome libraries and tools.
  - [**Best-of ML with Python**](https://github.com/lukasmasuch/best-of-ml-python): A ranked list of awesome machine learning Python libraries. 
  - [**Best-of ML with Julia**](https://github.com/e-tornike/best-of-ml-julia): A ranked list of awesome machine learning Julia libraries.
- [**Awesome list**](https://github.com/sindresorhus/awesome): An awesome list of awesome lists.
  - [**Awesome Python Data Science**](https://github.com/krzjoa/awesome-python-data-science): An awesome curated list of data science software in Python.

## Changed options from the best-of-generator

The following options were changed from the default settings of the [best-of-generator](https://github.com/best-of-lists/best-of-generator) for a better ranking and inclusion of projects:
| Option | Value | Default |
|---|---:|---:|
| `project_new_months` | 12 | 6 |
| `project_inactive_months` | 12 | 6 |
| `project_dead_months` | 24 | 12 |
| `min_stars` | 50 | 100 |
| `min_projectrank` | 5 | 10 |

## Generating the list

First, to generate the list, you'll need a free API key from - Get an API key from [libraries.io](https://libraries.io/api).

### Generating the list locally

To generate the list locally, follow these steps:
- Install the environment with `uv sync`
- Run the script with `uv run best-of generate -l your_API_key_here ./projects.yaml`

For now, it only worked on Linux/WSL. It might not work on Windows.

### Generating the list with GitHub Actions

To generate the list with GitHub Actions, follow these steps:
- Go to the repository settings, then `Secrets and Variables` > `Actions`.
- Add a new repository secret with the name `LIBRARIES_KEY` and your API key from libraries.io as the value.
- Go to the `Actions` tab of the repository.
- Run the `update-best-of-list` workflow. A Pull Request will be generated after a few minutes.
- Merge the Pull Request to update the list.

<!-- ## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/brunoml5/best-of-casadi/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/brunoml5/best-of-casadi/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/brunoml5/best-of-casadi/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/brunoml5/best-of-casadi/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/brunoml5/best-of-casadi/blob/main/.github/CODE_OF_CONDUCT.md). -->

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

Check the [License](https://github.com/brunoml5/best-of-casadi/?tab=CC-BY-SA-4.0-1-ov-file) tab for more info.
