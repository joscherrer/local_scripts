# Various scripts

This README explains how my custom scripts are meant to be used

# initrole

## Requirements

- cookiecutter

## Usage
```
Usage: /home/jscherrer/.local/scripts/initrole [-r|--role-name <arg>] [-t|--template <arg>] [--(no-)input] [-h|--help]
        -r, --role-name: Specify the role name (no default)
        -t, --template: Specify the role template (default: 'default')
        --input, --no-input: Ask for cookiecutter input (off by default)
        -h, --help: Prints help
```

Creates an ansible role from a template (with a molecule test folder).  
You need to provide a role name with --role-name

You can chose one of the templates from this list :

| Name    | URL                                                      |
|---------|----------------------------------------------------------|
| default | https://github.com/joscherrer/ansible-role-skeleton.git  |
| build   | https://github.com/joscherrer/ansible-role-skelbuild.git |

## To do

> Implement custom template by providing an URL