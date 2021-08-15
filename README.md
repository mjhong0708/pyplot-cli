# pyplot-cli

![Coverage Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/mjhong0708/13e2bab396cb1eb44f14dd08787f89bd/raw/pyplot-cli__heads_master.json)

Lightweight cli tool for plotting data. Currently, only line plot is supported.

## Release note

- `0.1.0` (2021.08.15): Initialized!
- `0.1.1` (2021.08.15): Fixed type checking issues

## Installation

- `pip install pyplot_cli` for installation from pypi
- download wheel from releases and install manually by pip

## Usage

- Basic: `pyplt [filename] -x [x_index] -y [y_indices]`
  - The form `-y`: index1,index2,...
- result:

    ![example](examples/example.png)

- more options: `--xlabel`, `--ylabel`, ... see `pyplt --help` for all options.
