# Configuration files

This repository contains some configurations files.

## List of file provided

- local.conf : a configuration file allowed launch locale
- slurm.conf : a configuration file allowed launch with slurm
- slurm_apptainer.conf : a configuration file allowed launch with slurm and apptainer

## Usage

`java -Xmx35g -Dconfig.file=backends.conf/slurm_apptainer.conf -jar cromwell.jar run workflow.wdl`
