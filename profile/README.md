# DDEX.net Suite

DDEX.net Suite develops a universal, uncompromising, extremely fast, reliable, open source implementation of the *DDEX Digital Sales Report Message Suite Standard* ([DSR](https://ddex.net/standards/sales-and-usage-reporting/))

## Motivation
> DDEX is a standards setting organisation focused on the creation of digital value chain standards to make the exchange of data and information across the music industry more efficient.

The existence of a Standard is a major step in data exchange communication across companies. Unfortunately, DDEX does not have the sources to develop and maintain a common, open source implementation of the standard.

Focusing on *DDEX Digital Sales Report Message Suite Standard* ([DSR](https://ddex.net/standards/sales-and-usage-reporting/)), as of December 2022, DDEX [acknowledges](https://kb.ddex.net/display/HBK/Open+Source+Software) an open source [DSR Flat File parser](https://github.com/ddexnet/dsrf), but it is not actively maintained.

**The goal** is to develop a universal, uncompromising, extremely fast, reliable, open source implementation of the *DDEX Digital Sales Report Message Suite Standard* ([DSR](https://ddex.net/standards/sales-and-usage-reporting/)).

* **Universal**. The same software can be used by parties generating files and consuming files. Both parties can discuss the same implementation and work together on a common solution, also easing conflict resolution. 
* **Uncompromising**. Software must be strict to comply with the format of the standard, but must be flexible about the contents.
* **Extremely fast, reliable**. Implemented in Rust, software is both reliable and fast.  
* **Open Source**. Contributions from all parties is valuable, welcomed and appreciated.

The suite will include:

* **DSR Parser**. Libraries to parse files in DSR format into native programming structures.
* **DSR Writer**. Libraries to write native programming structures to a file in DSR format.
* **DSR Testing**. Generate DSRs with random data for testing and benchmarking.
* **DSR Splitter**. Split files in DSR format having multiple contexts into many single-context files.
* **DSR Explorer**. GUI application to easily browse extremely large DSR files, similar to *[klogg](https://github.com/variar/klogg)*, with crystal clear documentation and validation hints.
* **DSR Multipart**. Split files in DSR format into multiple multipart files.
