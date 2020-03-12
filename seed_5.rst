Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 5

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.975465
 - Clean trial 2 run time: 0:00:04.184240
 - Mutation trials total run time: 0:00:37.924763

Overall mutation trial summary
==============================
 - SURVIVED: 10
 - TOTAL RUNS: 10
 - RUN DATETIME: 2020-03-12 16:11:31.870470


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/_win32_links.py: (l: 109, c: 8) - mutation from If_Statement to If_True
 - ubelt/util_cache.py: (l: 185, c: 11) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_dict.py: (l: 160, c: 28) - mutation from <class '_ast.Eq'> to <class '_ast.NotEq'>
 - ubelt/util_hash.py: (l: 219, c: 7) - mutation from <class '_ast.Or'> to <class '_ast.And'>
 - ubelt/util_import.py: (l: 661, c: 22) - mutation from Slice_UnboundLower to Slice_Unbounded
 - ubelt/util_links.py: (l: 127, c: 11) - mutation from <class '_ast.Eq'> to <class '_ast.NotEq'>
 - ubelt/util_list.py: (l: 108, c: 15) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_memoize.py: (l: 209, c: 36) - mutation from None to True
 - ubelt/util_memoize.py: (l: 287, c: 8) - mutation from If_Statement to If_True
 - ubelt/util_stream.py: (l: 29, c: 32) - mutation from None to False