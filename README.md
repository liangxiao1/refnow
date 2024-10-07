# refnow README

refnow provides often used snippets, eg. doc templates, code quick start.

## Installation

### Install from marketplace

Install from marketplace directly by searching 'refnow' or click [here](https://marketplace.visualstudio.com/items?itemName=FrankLiang.refnow).

```bash
# code --install-extension FrankLiang.refnow
```

### Install from source code

Copy code [repo](https://github.com/liangxiao1/refnow) into `~/.vscode/extensions` directly and restart VS Code.

### Build .vsix from source code and install it

```bash
# npm install -g vsce
# vsce package
# code --install-extension <myextension>.vsix
```

### Public new .vsix on [marketplace](https://marketplace.visualstudio.com/VSCode) (maintainer use only)

```bash
# vsce login FrankLiang
# vsce ls
# vsce package
# vsce publish
```

## Usage

Type `rf` to call supported snippsets.
![This is demo!](images/demo.gif "rf typed")

## Features

The list keeps updating.  

|Prefix | Description|
|-------|-------|
|rf_doc_case_checklist | TestCase best practice checklist, think more in new case design.
|rf_doc_case_docstring_yaml | Doc template for test case in yaml format.|
|rf_doc_case_docstring_csv | Doc template for test case in yaml format.|
|rf_py_argparse | Python argparse snippet|
|rf_py_concurrent.futures | Python run in parallel snippet|
|rf_py_csv_read | Python csv file dic read snippet|
|rf_py_csv_write | Python csv file dic write snippet|
|rf_py_filelock | Python filelock snippet|
|rf_py_logging | Python logging snippet|
|rf_py_signal | Python signal handler snippet|
|rf_py_timeout | Python timeout snippet|
|rf_py_yaml | Python yaml snippet|

## Contribution
You are welcome to share your expertise by creating pull requests or raise issues.  
Source on [github](https://github.com/liangxiao1/refnow).
