#  Ghidra-VMU-Processor
Ghidra Processor for disassembling/"decompiling" Dreamcast VMU binaries

![img](images/ghidra_listing.png)

## Using

Currently this only works with raw `.vms` binaries.

Copy the `LC8670` folder into the `$(GHIDRA_ROOT)/Ghidra/Processors/` directory; where `$(GHIDRA_ROOT)` is the location of your Ghidra installation. You will probably need to restart Ghidra to have the `LC8670` option appear when selecting the language option when importing a binary.