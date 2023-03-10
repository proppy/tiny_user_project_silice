# Tiny User Project

Template for submitting [TinyTapeout](https://tinytapeout.com) based projects to the [Open MPW shuttle](https://developers.google.com/silicon) program.

## Usage

1. [Generate](https://github.com/proppy/tiny_user_project/generate) a new project based on this template.

1. [Set GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part) `Sources` as `GitHub Actions`.

1. Edit [`main.si`](main.si) [Silice](https://github.com/sylefeb/Silice) algorithm.
   
1. Edit [`info.yaml`](info.yaml):
    - In `documentation`:
      - Update `inputs` to document the input wires of your top-level algorithm (clock and reset comes always first).
      - Update `outputs` to document the output wires of your top-level algorithm.

1. Commit, push and check the [![user_project_ci](https://github.com/proppy/tiny_caravel_user_project/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/proppy/tiny_caravel_user_project/actions/workflows/user_project_ci.yml) workflow summary (if successful a new commit including the hardened files will be automatically created).

1. [Submit](https://platform.efabless.com/projects/create?project_definition=Open+MPW&shuttle=MPW-8) your project github repository to the next [Open MPW shuttle](https://platform.efabless.com/shuttles/MPW-8).
