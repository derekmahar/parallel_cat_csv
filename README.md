# parallel_cat_csv

`parallel_cat_csv` reads a list of CSV file names from standard input and uses [GNU Parallel](https://www.gnu.org/software/parallel/) and script `cat_csv` to concatenate these CSV files in parallel processes.

## Requirements

* `cat_csv.cat` requires `getopt` which is in Ubuntu package [util-linux](https://packages.ubuntu.com/jammy/util-linux).
* `cat_csv.csvtk` requires [csvtk](https://bioinf.shenwei.me/csvtk/).
* `cat_csv.mlr` requires [Miller](https://miller.readthedocs.io/).
* `cat_csv.xsv` requires [`xsv`](https://github.com/BurntSushi/xsv).
* `parallel_cat_csv` requires [GNU Parallel](https://www.gnu.org/software/parallel/).
