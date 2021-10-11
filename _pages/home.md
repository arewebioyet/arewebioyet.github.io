---
title: Are we bio yet?
layout: single
permalink: /
---

🎉 Yes! 🎉

(but many projects are still work-in-progress)

The Rust bioinformatics ecosystem contains general, easy-to-use crates like [bio](https://crates.io/crates/bio), along with a plethora of crates for specific tasks.

## Ecosystem

### Libraries

Here you can find all sorts of bioinformatics crates that were created by the Rust community:

* [bio](https://crates.io/crates/bio) - Implementations of many useful bioinformatics data structures and algorithms, including pattern matching, alignment, suffix arrays, BWT, FM-Index, and parsers for common file types.
* [coitrees](https://crates.io/crates/coitrees) - Cache oblivious interval tree implementation for very fast overlap queries of a static set of integer intervals, with genomic intervals in mind.
* [debruijn](https://crates.io/crates/debruijn) - De Bruijn graph construction & path compression libraries.
* [htsget-rs](https://github.com/umccr/htsget-rs) - GA4GH's [htsget](https://samtools.github.io/hts-specs/htsget.html) implementation.
* [needletail](https://crates.io/crates/needletail) - Fast FASTX parsing and k-mer methods in Rust.
* [noodles](https://github.com/zaeleus/noodles) - Pure Rust bioinformatics I/O libraries.
* [rust-htslib](https://crates.io/crates/rust-htslib) - Provides HTSlib bindings and a high level Rust API for reading and writing BAM files.
* [triple_accel](https://crates.io/crates/triple_accel) - Rust edit distance routines accelerated using SIMD. Supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search.
* [fastq-rs](https://github.com/aseyboldt/fastq-rs) - A fast parser for FASTQ.
* [seq_io](https://github.com/markschl/seq_io) - FASTA and FASTQ parsing and writing in Rust.

### Tools

Here you can find all sorts of bioinformatics tools that were created by the Rust community:

* [alevin-fry](https://github.com/COMBINE-lab/alevin-fry) - A suite of tools for processing single-cell sequencing data.
* [bamtofastq](https://github.com/10XGenomics/bamtofastq) - Tool for converting 10x BAMs produced back into to FASTQ files.
* [bcl2fastr](https://github.com/czbiohub/bcl2fastr) - Faster bcl2fastq implementation.
* [finch](https://github.com/onecodex/finch-rs) - A genomic MinHashing implementation.
* [fmlrc2](https://crates.io/crates/fmlrc) - A tool for correcting long, noisy reads from short reads
* [noodles-squab](https://github.com/zaeleus/noodles-squab) - Noodles squab performs gene expression quantification by counting the number of aligned records that intersects a set of features. Output can be the raw counts or normalized counts in TPM (transcripts per million) or FPKM (fragments per kilobase per million mapped reads).
* [perbase](https://crates.io/crates/perbase) - A highly parallelized utility for generating per-base level metrics.
* [prosolo](https://github.com/ProSolo/prosolo) - A variant caller for multiple displacement amplified DNA sequencing data from diploid single cells
* [rust-mdbg](https://github.com/ekimb/rust-mdbg) - Minimizer-space de Bruijn graphs (mdBG) implementation for whole-genome assembly.
* [sourmash](https://github.com/dib-lab/sourmash) - Quickly search, compare, and analyze genomic and metagenomic data sets.
* [varlociraptor](https://crates.io/crates/varlociraptor) - Varlociraptor implements a novel, unified fully uncertainty-aware approach to genomic variant calling in arbitrary scenarios.

## Contributing

You can use the [editor on GitHub](https://github.com/arewebioyet/arewebioyet.github.io/edit/main/_pages/home.md) to contribute to this page. Feel free to list new bioinformatics crates! Of course, you can also contribute to the ecosystem by writing a new Rust crate.
