# Defra FFC Mac Scripts
Scripts for automating the process of setting up a MacBook for local development within Defra's FFC programme. Note that some packages such as kubelogin and yq are not mandatory packages listed in the [ffc-development-guide](https://github.com/DEFRA/ffc-development-guide/blob/main/docs/local-development-setup/index.md), but are still useful to have installed. Below is a summary for what each script can do (it's recommended to run the scripts in the order presented in the table):
| Script | Description | Command |
| -------------- | ------------------------------------------------------------------------------------ | ------- |
| `bulk-install` | Bulk installing most of the packages required in the [ffc-development-guide](https://github.com/DEFRA/ffc-development-guide/blob/main/docs/local-development-setup/index.md). Installs Command Line Tools & Homebrew. Also installs kubectl, kubelogin, Helm, Azure CLI, Snyk CLI, GitHub CLI, and yq (all using Homebrew).  | `./bulk-install` |
| `check-version` | Checks version of each package installed using the `bulk-install` script. | `./check-version` |
| `install-detect-secrets` | Script that will install Python, pip, pre-commit, and detect-secrets. | `./install-detect-secrets` |

