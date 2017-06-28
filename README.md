# TuberculosisWGSDataProcessorVersionImprovedJune2017

Software is designed for the rational, fast and robust data processing (SNP/Indel variant calling and mutation profiling) of the whole genomes of tuberculosis. 

It takes a SRA identifier of the Tuberculosis sample and runs a pipeline of the open-source aligners, converters, variant callers and the SNPEff annotation engine. The results are annotated VCFs, gene lists and intermediate files you can use in your work and studies. You can remake software to use it for a human genome or the genome of any organism. If you are able to write and run Python and Linux Shell codes you can add your bionformatics tools in a similar straightforward manner I show in these codes.

Put files in one folder on a Linux machine and run Execute.py (preset it to work as executable file).

You can use BioLinux .ova for running the software, otherwise you have to install several dependencies (use sudo-apt get install and Python`s pip tool).

Software has a functionality to put the output results to the MegaNZ free cloud storage (you need to write your account data in Execute.py instead of my personal data written therein in the lines 63-70, "uploadtocloud" function).

Thank you for attention

Software has no documentation yet


Ask help (me) and your computer professionals

Matvey Sprindzuk, software developer, MD

msprindzhuk@mail.ru

