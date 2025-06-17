# niwrap-workshop

Welcome to the repository for the interactive [`niwrap`] workshop!

This workshop showcases how to use [`niwrap`] through a series of hands-on examples
provided as [Jupyter] notebooks. All necessary data for running the examples is
included in the repository.

To run the examples, some neuroimaging tools must be available - see
[Required neuroimaging tools](#required-neuroimaging-tools) for more details. These
can be accessed via local installations, [Docker], or [Singularity].

- If the necessary tools are already installed on your local machine or [Docker] is
  available, you're all set - no further setup is needed.
- If you plan to use [Singularity], a few additional setup steps are required - don't
  worry, detailed instructions are provided below!

## Getting started

To run examples, the only prerequisite is to be able to run a [Jupyter] notebook.
It is recommended to clone this repository, create a virtual environment and install
[Jupyter].

```sh
# Clone and navigate to directory
git clone https://github.com/styx-api/niwrap-workshop niwrap-workshop
cd niwrap-workshop

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Install Jupyter
pip install jupyter
```

## Required neuroimaging tools

- [`ANTs`]
- [`FSL`]

<!-- Links -->

[Docker]: https://www.docker.com/
[Jupyter]: https://jupyter.org/
[`niwrap`]: https://github.com/styx-api/niwrap
[Singularity]: https://apptainer.org/
[`ANTs`]: https://github.com/ANTsX/ANTs
[`FSL`]: https://fsl.fmrib.ox.ac.uk/fsl/docs/#/
