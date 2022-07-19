# Welcome to Drone Tutorial

## Highlighting

{==REMOVE THE SECTION BELOW AFTER TUTORIAL IS COMPLETE.==}

{--Deleted--} {++added++} {~~one~>a single~~} 

## Keys 

++cmd+alt+del++ or ++ctrl+alt+del++

## Smart Symbols

 - Trademark(tm)
 - Copyright(c)

## Mkdocs Info

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
    includes/     # All include files will here, the includes files will can be added using 

## Extensions

```yaml
kind: Pipeline
type: Docker
name: default
steps:
   - name: say hello
     image: busybox
     commands:
       - echo "Hello World"
```

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! warning

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! important

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

## Theme

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/reference/)

--8<--​ "includes/abbrevations.md"
