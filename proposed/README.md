# Proposed Extensions

This directory contains the specifications for SYCL extensions that are supported for the Samsung Computational Memory device. These specifications can be implemented in DPC++ (SYCL in Intel), but they've not been implemented yet. These extension documents are published here to gather community feedback.

When a proposed extension is implemented, the specification document is generally moved to either the "supported" or "experimental" directory, and there may also be some changes to its APIs.


To create PDF from the ASCIIDoc format, run asciidoctor-pdf ****.adoc after installing asciidoctor.
```
sudo apt install asciidoctor
sudo apt install ruby-asciidoctor-pdf
sudo gem install pygments.rb

asciidoctor-pdf test.adoc
``` 

Or you can get some help from https://docs.asciidoctor.org/pdf-converter/latest/install/.
When you use the Windows system, this link (https://github.com/asciidoctor/asciidoctor-pdf/issues/2) would be helpful.

