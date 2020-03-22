# Education Arena

Documentation and workspace for the development and deployment of *Education Game*.

## Table of Contents <!-- omit in toc -->

- [Education Arena](#education-arena)
  - [Workspace Setup](#workspace-setup)
  - [Documentation](#documentation)
    - [How to use each repository together](#how-to-use-each-repository-together)
      - [Zageron's UI Framework](#zagerons-ui-framework)

## Workspace Setup

1. Clone the following repositories:
   - [git@github.com:rhythm-collective/arena.git](git@github.com:rhythm-collective/arena.git)
   - [git@github.com:Zageron/zui.git](git@github.com:Zageron/zui.git)
   - [git@github.com:Zageron/blender-to-mongo-scene-composition.git](git@github.com:Zageron/blender-to-mongo-scene-composition.git)

1. Lay them out in the following structure:

    ``` bash
    | -- .
        | -- arena
        | -- zui
        | -- blender-mongo
    ```

1. Simplified commands.

    ``` bash
    cd /path/to/parent/directory/of/this/repository
    git clone git@github.com:rhythm-collective/arena.git arena
    git clone git@github.com:Zageron/zui.git zui
    git clone git@github.com:Zageron/blender-to-mongo-scene-composition.git blender-mongo
    ```

1. Open Visual Studio Code

1. Open the education-arena workspace.

1. Install the recommended extensions.

## Documentation

### How to use each repository together

#### Zageron's UI Framework

ZUI is a typescript project which utilizes p5.js for rendering all user facing interfaces. This is not limited to just standard *UI*, but includes all rendering for a project.

ZUI supports workerized browser jobs, and encourages them.

Attempts to segregate interaction logic, layout logic, and rendering logic to prevent hard-coded stuff. This may be functional.
