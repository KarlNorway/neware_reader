# neware_reader
This is a simple binary reader for Neware .nda files. It is based on the excellent work already done by thebestpatrick, who published the nda-extractor package in 2015. This package updates the exiting package and allows it to read the newest .nda files

The package currently does two things:
1. Read a .nda directly into Python as a pandas DataFrame. read_nda('input.nda') Among the columns created is a 'step_ID' which increases on a step change. This is the unique identifier for each step.

2. Output a .csv from an .nda input file with nda_to_csv('input.nda')
