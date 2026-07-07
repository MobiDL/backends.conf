# Configuration files

This repository contains some configurations files.

## List of file provided

- local.conf : a configuration file allowed launch locale
- slurm.conf : a configuration file allowed launch with slurm
- slurm_apptainer.conf : a configuration file allowed launch with slurm and apptainer

## Added to a new workflow

To improve usability, reproducibility and maintainability, it is recommended that you include this repository in all workflows as follows: 
`git submodule add https://github.com/MobiDL/backends.conf`

And updates as follow :
`git submodule update --remote backends.conf`

## Usage

`java -Xmx35g -Dconfig.file=backends.conf/slurm_apptainer.conf -jar cromwell.jar run workflow.wdl`
