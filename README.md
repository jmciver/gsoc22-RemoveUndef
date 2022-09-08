# GSoC22 - Remove undef: Move Uninitialized Memory to Poison

This repository contains documention in support of GSoC22 project "Remove undef: Move Uninitialized Memory to Poison".

## Documents

* [Final report for period of performance](https://raw.githubusercontent.com/jmciver/gsoc22-documentation/master/GSoC_2022_LLVM_Final_Report.pdf)

## LLVM Patches

* [D128501: \[CodeGen\] Make uninitialized Lvalue bit-field stores poison compatible](https://reviews.llvm.org/D128501)
* [D129541: \[llvm\]\[IPO\] Add IR function attribute fine_grained_bitfields](https://reviews.llvm.org/D129541)
* [D129542: \[CodeGen\] Add codegen of IR function attribute fine\_grained\_bitfields](https://reviews.llvm.org/D129542)

## Discourse

* [Remove undef: move uninitialized memory to poison](https://discourse.llvm.org/t/remove-undef-move-uninitialized-memory-to-poison/61123)
* [\[RFC\] Making Bit-field Codegen Poison Compatible](https://discourse.llvm.org/t/rfc-making-bit-field-codegen-poison-compatible/63250)

## LLVM GitHub Tickets

* [\#56646: LLVM Codegen producing extra move instructions or crashing with freeze](https://github.com/llvm/llvm-project/issues/56646)
