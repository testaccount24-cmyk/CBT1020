# CBT1020
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1020 is from Steve Myers and contains a program to cross   *   FILE1020
//*           reference a large number of assembler listings, and   *   FILE1020
//*           to report the occurrence of variables, across the     *   FILE1020
//*           whole collection.                                     *   FILE1020
//*                                                                 *   FILE1020
//*           email:  Steve Myers <mvsprog@yahoo.com>               *   FILE1020
//*                                                                 *   FILE1020
//*     Product Description:                                        *   FILE1020
//*                                                                 *   FILE1020
//*     GBLXREF is a tool to contruct a global XREF of Assembler    *   FILE1020
//*     systems containing multiple modules.  GBLXREF was           *   FILE1020
//*     developed for JES2.  It is a viable replacement for         *   FILE1020
//*     XREFASM in CBT file 162.                                    *   FILE1020
//*                                                                 *   FILE1020
//*     The original inspiration for GBLXREF was a global symbol    *   FILE1020
//*     table in some PLM manuals for HASP-II Version 4.  Early     *   FILE1020
//*     versions of GBLXREF were much like the XREFASM utility      *   FILE1020
//*     in "file" 162 of the CBT collection, except it could        *   FILE1020
//*     process both Assembler H output as well as output from      *   FILE1020
//*     the OS/VS System Assembler, more commonly called the        *   FILE1020
//*     IFOX assembler.                                             *   FILE1020
//*                                                                 *   FILE1020
//*     The SYSADATA output created by Version 1.4 of the High      *   FILE1020
//*     Level Assembler suggested useful enhancements: the          *   FILE1020
//*     ability to detect and report symbols that were modified,    *   FILE1020
//*     and resistance to changes in Assembler output.  A few       *   FILE1020
//*     minor changes were required to support High Level           *   FILE1020
//*     Assembler release 5, though no changes were required for    *   FILE1020
//*     release 6.                                                  *   FILE1020
//*                                                                 *   FILE1020
//*     The process to run something like GBLXREF suggested         *   FILE1020
//*     several processing requirements.                            *   FILE1020
//*                                                                 *   FILE1020
//*     - There must be a method to determine the global            *   FILE1020
//*       symbols; in HASP and JES2 these symbols are in module     *   FILE1020
//*       HASPDOC.                                                  *   FILE1020
//*                                                                 *   FILE1020
//*     - To simplify JCL, there must be a utility to prepare       *   FILE1020
//*       the ADATA data set in as few steps as possible, as        *   FILE1020
//*       well as reduce the volume of data in the ADATA data       *   FILE1020
//*       set.                                                      *   FILE1020
//*                                                                 *   FILE1020
//*          C O N T E N T S   O F   T H I S   D A T A S E T        *   FILE1020
//*                                                                 *   FILE1020
//*     Member     Purpose                                          *   FILE1020
//*     $DOC     - This member                                      *   FILE1020
//*     ASMJES2  - JCL to assemble JES2 and then run the GBLXREF    *   FILE1020
//*                utility.  The space allocations in the JCL       *   FILE1020
//*                work well for JES2 in z/OS 2.5.                  *   FILE1020
//*     GBLXREF  - Source for the GBLXREF utility                   *   FILE1020
//*     GENXREF  - JCL to assemble and link GBLXREF and the         *   FILE1020
//*                other programs in this collection                *   FILE1020
//*     JESASM   - Source for the utility to assemble source        *   FILE1020
//*                modules and prepare the ADATA data set for       *   FILE1020
//*                GBLXREF                                          *   FILE1020
//*     MEMBLIST - Source for the utility to create a JESASM        *   FILE1020
//*                CONTROL data set                                 *   FILE1020
//*     MINIFMT  - Source for functions used by GBLXREF to          *   FILE1020
//*                create messages                                  *   FILE1020
//*     OBJASM   - Object "decks" for JESASM                        *   FILE1020
//*     OBJXREF  - Object "decks" for GBLXREF                       *   FILE1020
//*     OBJMLIST - Object "deck" for MEMBLIST                       *   FILE1020
//*     QSORTS   - Source for functions used by GBLXREF to sort     *   FILE1020
//*                data                                             *   FILE1020
//*     REPORT   - A typical GBLXREF report.  This member is        *   FILE1020
//*                compressed data in XMIT format.                  *   FILE1020
//*     RUNXREF  - JCL to run the GBLXREF utility.                  *   FILE1020
//*                                                                 *   FILE1020
```
