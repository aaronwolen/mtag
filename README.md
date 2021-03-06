# `mtag` (Multi-Trait Analysis of GWAS)

`mtag` is a Python-based command line tool for jointly analyzing multiple sets of GWAS summary statistics as described by [Turley et. al. (2017)](http://www.biorxiv.org/content/early/2017/07/03/118810). It can also be used as a tool to meta-analyze GWAS results.

## Getting Started

We recommend installing the [Anaconda python distribution](https://www.continuum.io/downloads) as it includes all of the packages listed above. It also makes updating packages relatively painless with the `conda update` command.

To run `mtag`, you will need to have Python 2.7 installed with the following packages:

* `numpy`
* `scipy`
* `pandas`
* `argparse`
* `bitarray` (for `ldsc`)
* `joblib`



`mtag` may be downloaded by cloning this github repository:

	git clone https://github.com/omeed-maghzian/mtag.git

To test that the tool has been successfully installed, type:

	./mtag.py -h

You should see a list of command-line flags and a description of the program. If an error is thrown instead, then there was some problem with the installation process.

A tutorial that walks through an example use of `mtag` may be found in the wiki.

### Updating `mtag`

The easiest was to update `mtag` is through `git`. When you are in the `mtag/` directory, simply enter

	git pull

which will update the `mtag` files. If there have been no new updates since the last download of `mtag` then the terminal will print: `Already up-to-date.`

### Support

We will try our best to address any problems that one may encounter when using `mtag`. However, before [opening an issue](https://github.com/omeed-maghzian/mtag/issues) or emailing us, please first:

1. Read the wiki, especially the tutorial and FAQ pages
2. Read the desciption of the method in the paper listed below

If that doesn't prove to be enlightening, then feel free to post a question on our [Google Groups page](https://groups.google.com/forum/#!forum/mtag_users) or [contact us](mailto:maghzian@nber.org). The more information you provide about your problem, the more helpful we can be!

### Citation

If you use the `mtag` software or methodology, please cite:

Turley, et. al. MTAG: Multi-Trait Analysis of GWAS. bioRxiv doi: <https://doi.org/10.1101/118810>.

### License

This project is licensed under GNU General Public License v3.

### Authors

Omeed Maghzian (Harvard University, Department of Economics)

Raymond Walters (Broad Institute of MIT and Harvard)

Patrick Turley (Broad Institute of MIT and Harvard)

### Acknowledgments

The development of this software was carried out under the auspices of the Social Science Genetic Association Consortium (SSGAC). This work was supported by the Ragnar Söderberg Foundation (E9/11 E42/15), the Swedish Research Council (421-2013-1061), The Jan Wallander and Tom Hedelius Foundation, an ERC Consolidator Grant (647648 EdGe), the Pershing Square Fund of the Foundations of Human Behavior, the National Science Foundation’s Graduate Research Fellowship Program (DGE 1144083), and the NIA/NIH through grants P01-AG005842, P01-AG005842-20S2, P30-AG012810, and T32-AG000186-23 to NBER, R01-AG042568-02 to the University of Southern California, and 1R01MH107649-01and 1R01MH101244-02 to the Broad Institute at Harvard and MIT. 

