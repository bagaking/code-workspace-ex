# README

Code Workspace Extern project

## Requirement

- Node.js > 8.0
- make
- git (for update)

## Installation

in the folder you want to install the tool, run commond

```sh
git clone https://github.com/bagaking/code-workspace-ex.git .code-workspace-ex && /bin/bash -c ./.code-workspace-ex/install.sh
```

### by curl

```sh
curl -LJO https://raw.githubusercontent.com/bagaking/code-workspace-ex/archive/master.zip
```

## Update

To update the code-worksapce-ex, you can easilly remove(or backup if there are some custom changes) the old `.code-workspace-ex` folder, and install it by your prefer command again.

e.g.

```sh
rm -rf .code-workspace-ex && git clone git@github.com:bagaking/code-workspace-ex.git .code-workspace-ex && /bin/bash -c ./.code-workspace-ex/install.sh
```

If git are used in the installation stage, you can also using the command `code-workspace-ex-update` in the makefile

```sh
make code-workspace-ex-update
```

## Contribution

pull request is welcome

## Contact

e-mail: kinghand@foxmail.com

## Lisence

Released under the MIT License
