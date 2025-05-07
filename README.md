# git-ignore

Shell Script and Git alias to select and install a remote `.gitignore` template.

## Installation

```shell
curl -O -L -P /path/to/dir https://raw.githubusercontent.com/mc7h/git-ignore/main/git-ignore
```

> [!NOTE]
> git will auto-detect `ignore` as a subcommand if `git-ignore` is in the PATH.

## Usage

```shell
git ignore [query]
```

Set `FORCE_GI_PULL=1` to ensure the gitignore cache is updated.

## Demo

![git-ignore Terminal demo video](demo.gif)

1. Interactively filter available templates.
1. Provide filter at call-site. 
1. Auto-selects if there's only one match.

