# Welcome to SNG Diffusion Pipeline's user documentation!

This pipeline provides a streamlined way of processing diffusion weighted images (and as a side effect, structural images) through the *MRtrix*, *FSL* and *FreeSurfer* packages.

## Setup Information

1) Ensure that you are in your home directory on the avalon cluster::

  `$ cd ~`
	
2) Install the github package:

  `$ git clone https://github.com/AlistairPerry/dwi2connectome.git`


## Getting started

[Conversion to NiFTI for T1](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/structural_preprocessing/conversion_to_nifti.rst)

[Conversion to MIF for DWI](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/dwi_preprocessing/conversion_to_mif.md)

## Structural image preprocessing

[FreeSurfer preprocessing](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/structural_preprocessing/t1_processing_in_freesurfer.rst)

## Diffusion image preprocessing

[Advanced preprocessing](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/dwi_preprocessing/advanced_preprocessing.md)

[Segmentation and parcellation](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/dwi_preprocessing/segmentation_and_parcellation.md)

[Fibre and connectome construction](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/dwi_preprocessing/fibre_and_connectome_construction.md)

## Fixel-based analysis

[Fixel processing pipeline](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/fixel_based_analysis/processing_fixels.md)

[Fixel statistics](docs/fixel_stats.md)

## Quality checking

[Quality checking of images](https://github.com/AlistairPerry/dwi2connectome/blob/master/docs/quality_checking/qc.md)

## Troubleshooting

[Bugs and errors](docs/bugs.md)

[FAQs](docs/faqs.md)

[Fixel-based analysis](docs/fba.md)

## Tips and Tricks

[Bash commands](docs/bash_commands.md)

[Interactive sessions on Avalon](docs/interactive.md)


All processed files (images, matrices, text files) can be found in:

`/working/your_lab_here/your_working_dir/Diff/your_sub/preproc/`.


