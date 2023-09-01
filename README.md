# PrecisionTox Range finding drc



## The PrecisionTox concentration-response modelling for range finding data

Within the EU project PrecisionTox mortality, immobilisation and cytotoxicity as toxicity endpoints are generated from various small organisms and human cell cultures. The organisms are exposed to various concentrations of chemicals and the data are used to derive bench mark concentrations from concentration response modelling. The modelling is based on an R script which is embedded in a KNIME workflow. Users have to add their data using a template. The KNIME workflow is designed for execution on a KNIME server (at least version >4.15) but it is also possible to run it natively on KNIME analytics platform (at least versions >4.5). Earlier KNIME versions may work but have not been tested.

## Provided files and templates

This gitlab repository provides the KNIME workflow, a template for uploading the data and instructions to execute the workflow.

## Requirements

KNIME server or KNIME analytics installed and R version 4.2 (other versions may work). R packages drc and bmd need to be installed.

## Authors and acknowledgment
I acknowledge the EU project PrecisionTox and its partners for comments and suggestions to improve the workflow. The workflow was created using funds from the European Union’s Horizon 2020 research and innovation programme under Grant Agreement No 965406 (PrecisionTox). This output reflects only the authors’ view and the European Union cannot be held responsible for any use that may be made of the information contained therein.

## License
Public GNU3 license.

## Project status
No further developments planned for the workflow, potential bugs will be corrected.
