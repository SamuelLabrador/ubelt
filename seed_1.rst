Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 1

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.368938
 - Clean trial 2 run time: 0:00:03.390258
 - Mutation trials total run time: 0:01:20.784737

Overall mutation trial summary
==============================
 - SURVIVED: 5
 - DETECTED: 20
 - TOTAL RUNS: 25
 - RUN DATETIME: 2020-03-09 16:22:48.896836


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/_win32_links.py: (l: 455, c: 4) - mutation from If_Statement to If_True
 - ubelt/progiter.py: (l: 324, c: 32) - mutation from None to True
 - ubelt/progiter.py: (l: 358, c: 32) - mutation from True to None
 - ubelt/util_hash.py: (l: 934, c: 11) - mutation from <class '_ast.Gt'> to <class '_ast.GtE'>
 - ubelt/util_path.py: (l: 262, c: 18) - mutation from None to True


DETECTED
--------
 - ubelt/util_cache.py: (l: 185, c: 11) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_format.py: (l: 498, c: 9) - mutation from If_Statement to If_True
 - ubelt/util_format.py: (l: 498, c: 9) - mutation from If_Statement to If_False
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.Div'>
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.Sub'>
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.Mult'>
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.FloorDiv'>
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.Pow'>
 - ubelt/util_format.py: (l: 734, c: 22) - mutation from <class '_ast.Add'> to <class '_ast.Mod'>
 - ubelt/util_hash.py: (l: 934, c: 11) - mutation from <class '_ast.Gt'> to <class '_ast.Eq'>
 - ubelt/util_hash.py: (l: 934, c: 11) - mutation from <class '_ast.Gt'> to <class '_ast.Lt'>
 - ubelt/util_hash.py: (l: 934, c: 11) - mutation from <class '_ast.Gt'> to <class '_ast.LtE'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.Mult'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.Div'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.Sub'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.FloorDiv'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.Pow'>
 - ubelt/util_path.py: (l: 203, c: 19) - mutation from <class '_ast.Add'> to <class '_ast.Mod'>
 - ubelt/util_stream.py: (l: 120, c: 45) - mutation from True to False
 - ubelt/util_stream.py: (l: 120, c: 45) - mutation from True to None