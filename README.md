# LFG/XLE Grammars for Chinese

Author: Chit Fung LAM (Lawrence)

This project contains LFG grammar fragments developed in the Lexical-Functional Grammar formalism. They are implemented in the Xerox Linguistic Environment (XLE) to computationally model syntactic analyses of linguistic phenomena in Mandarin Chinese. See https://ling.sprachwiss.uni-konstanz.de/pages/xle/ for more information about grammar engineering via XLE, including how to download and use XLE.

LFG/XLE Grammar for Chinese Aspect under Control and Inner Topicalisation
-------------------------------------------------------------------------
This directory contains an LFG grammar implemented via the Xeror Linguistic Environment (XLE) to model two linguistic phenomena in Mandarin Chinese, namely Aspect under Control and Inner Topicalisation.

For reference to this grammar, please cite:

Lam, Chit Fung. 2022. ‘Control Complements in Parallel Constraint-based Architecture: Re-analysis of Two “Restructuring” Phenomena in Mandarin Chinese’. Conference paper presented at the 27th International Lexical-Functional Grammar Conference (LFG’22), University of Groningen, July 12-14.

  Important files in the directory
  --------------------------------
  1. restructuring.lfg
  
  This is the LFG grammar to be run by XLE.
  A html version is also included for displaying the content using a web browser.

  2. testsuite.lfg
  
  This testsuite contains the essential sentences to be parsed by the LFG grammar.
  A html version is also included for displaying the content using a web browser.

  Coverage of restructuring.lfg
  -----------------
  This is a small LFG grammar designed to parse the following sentence structures. See testsuite.lfg for the relevant exmaple sentences which illustrate the structures.

  1. Simple SVO
  2. Exhaustive control without Inner Topicalisation
  3. Partial control without Inner Topicalisation
  4. Non-control without Inner Topicalisation
  5. Exhaustive control with Inner Topicalisation
  6. Partial control with Inner Topicalisation
  7. Non-control with Inner Topicalisation
  8. Exhaustive control with Aspect under Control
  9. Partial control with Aspect under Control
  10. Exhaustive control with Inner Topicalisation and Aspect under Control
  11. Partial control with Inner Topicalisation and Aspect under Control
