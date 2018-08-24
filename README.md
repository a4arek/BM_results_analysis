# RTCI_results_analysis

1. We parse the BusMezzo output to pandas readable csvs (most of it, ca. 90%)
2. We parse the BusMezzo input to pandas readable csvs (most of it, ca. 70%)
3. We load the BusMezzo resutls to pandas DatFrame and have fun with them

See showcase in: https://github.com/a4arek/RTCI_results_analysis/blob/master/analyzer.ipynb

Constirubtion welcomed

TODO:

- Regex for nested "{}" parsing, identifying table begin and end, multiline rows, empty lines, etc. - seeparse_dat method in input_arses.ipynb

- Missing output files parsers , e.g.  'o_selected_paths.dat'



