Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 4

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.468556
 - Clean trial 2 run time: 0:00:03.471654
 - Mutation trials total run time: 0:00:51.020344

Overall mutation trial summary
==============================
 - DETECTED: 9
 - ERROR: 1
 - SURVIVED: 6
 - TOTAL RUNS: 16
 - RUN DATETIME: 2020-03-09 16:31:07.102520


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/_win32_links.py: (l: 27, c: 0) - mutation from If_Statement to If_False
 - ubelt/_win32_links.py: (l: 534, c: 39) - mutation from True to None
 - ubelt/orderedset.py: (l: 279, c: 19) - mutation from <class '_ast.GtE'> to <class '_ast.NotEq'>
 - ubelt/progiter.py: (l: 575, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Div'>
 - ubelt/util_download.py: (l: 225, c: 59) - mutation from False to True
 - ubelt/util_format.py: (l: 659, c: 40) - mutation from None to False


DETECTED
--------
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.FloorDiv'>
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Div'>
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Pow'>
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Mult'>
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Add'>
 - ubelt/util_arg.py: (l: 60, c: 12) - mutation from <class '_ast.Sub'> to <class '_ast.Mod'>
 - ubelt/util_cache.py: (l: 638, c: 11) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_list.py: (l: 491, c: 38) - mutation from Slice_UnboundUpper to Slice_Unbounded
 - ubelt/util_list.py: (l: 491, c: 38) - mutation from Slice_UnboundUpper to Slice_UnboundLower


ERROR
-----
 - ubelt/progiter.py: (l: 97, c: 3) - mutation from <class '_ast.Gt'> to <class '_ast.Lt'>