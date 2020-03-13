Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 6

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.819339
 - Clean trial 2 run time: 0:00:05.886618
 - Mutation trials total run time: 0:01:31.595794

Overall mutation trial summary
==============================
 - DETECTED: 11
 - SURVIVED: 7
 - TOTAL RUNS: 18
 - RUN DATETIME: 2020-03-12 18:33:14.393114


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/__main__.py: (l: 13, c: 0) - mutation from If_Statement to If_True
 - ubelt/_win32_links.py: (l: 172, c: 16) - mutation from If_Statement to If_True
 - ubelt/orderedset.py: (l: 129, c: 28) - mutation from <class '_ast.Mod'> to <class '_ast.Pow'>
 - ubelt/progiter.py: (l: 490, c: 25) - mutation from <class '_ast.Sub'> to <class '_ast.Add'>
 - ubelt/util_cache.py: (l: 239, c: 28) - mutation from None to False
 - ubelt/util_import.py: (l: 81, c: 8) - mutation from If_Statement to If_True
 - ubelt/util_path.py: (l: 230, c: 57) - mutation from False to None


DETECTED
--------
 - ubelt/util_format.py: (l: 683, c: 40) - mutation from Slice_UnboundUpper to Slice_Unbounded
 - ubelt/util_format.py: (l: 683, c: 40) - mutation from Slice_UnboundUpper to Slice_UnboundLower
 - ubelt/util_links.py: (l: 186, c: 15) - mutation from True to None
 - ubelt/util_links.py: (l: 186, c: 15) - mutation from True to False
 - ubelt/util_path.py: (l: 230, c: 57) - mutation from False to True
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.Mult'>
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.Div'>
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.Mod'>
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.FloorDiv'>
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.Pow'>
 - ubelt/util_str.py: (l: 189, c: 56) - mutation from <class '_ast.Add'> to <class '_ast.Sub'>