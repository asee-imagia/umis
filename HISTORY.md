## 0.5.0 (in progress)


## 0.4.0

- Fix for handling unicode, thanks to @chapmanb and @sowmyaiyer
- Adds support for adding BAM tags to aligned fastqtransformed files. Thanks to @chapmanb.
- Adds support for UMI-only fastqtransformation.
- Adds support for paired-end target sequences.
- Adds support for detecting sample barcodes via the SB tag in the regex.
- Adds support for sample-based demultiplexing with error correction.

## 0.3.0

- Now supports transforming 3-file input, as from the Linnarsson lab STRT-Seq data
- New kallisto subcommand formats read files for input to kallisto's UMI mode
- Fix gzip based fastq reading on Python 3.5
- Including preliminary subcommand for guessing cell cutoff from cb_histogram

## 0.2.2

- Added MANIFEST file which broke pip installation