# `data` folder

The following files belong here to run `abcd2bids.py`:

1. `CHANGES`
1. `dataset_description.json`
1. `task-MID_bold.json`
1. `task-nback_bold.json`
1. `task-rest_bold.json`
1. `task-SST_bold.json`

Without these files, the output of `abcd2bids.py` will fail BIDS validation. They should be downloaded from the GitHub repo by cloning it.

This folder is where the output of `abcd2bids.py` will be placed by default. So, after running `abcd2bids.py`, this folder will have subdirectories for each subject session. Those subdirectories will be correctly formatted according to the [official BIDS specification standard v1.2.0](https://github.com/bids-standard/bids-validated).

The resulting ABCD Study dataset here is made up of all the ABCD Study participants' imaging data that passed initial acquisition quality control (MRI QC).