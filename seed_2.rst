Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 2

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.390172
 - Clean trial 2 run time: 0:00:03.427509
 - Mutation trials total run time: 0:01:25.164144

Overall mutation trial summary
==============================
 - SURVIVED: 3
 - DETECTED: 23
 - TOTAL RUNS: 26
 - RUN DATETIME: 2020-03-09 16:26:19.015593


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/_win32_links.py: (l: 390, c: 24) - mutation from None to False
 - ubelt/util_links.py: (l: 225, c: 13) - mutation from If_Statement to If_True
 - ubelt/util_stream.py: (l: 171, c: 26) - mutation from None to False


DETECTED
--------
 - ubelt/orderedset.py: (l: 189, c: 8) - mutation from If_Statement to If_False
 - ubelt/orderedset.py: (l: 189, c: 8) - mutation from If_Statement to If_True
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.FloorDiv'>
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.Mult'>
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.Add'>
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.Pow'>
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.Div'>
 - ubelt/orderedset.py: (l: 307, c: 19) - mutation from <class '_ast.Mod'> to <class '_ast.Sub'>
 - ubelt/progiter.py: (l: 643, c: 25) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_cache.py: (l: 180, c: 11) - mutation from <class '_ast.And'> to <class '_ast.Or'>
 - ubelt/util_cache.py: (l: 652, c: 25) - mutation from <class '_ast.NotEq'> to <class '_ast.LtE'>
 - ubelt/util_cache.py: (l: 652, c: 25) - mutation from <class '_ast.NotEq'> to <class '_ast.Eq'>
 - ubelt/util_cache.py: (l: 652, c: 25) - mutation from <class '_ast.NotEq'> to <class '_ast.GtE'>
 - ubelt/util_cache.py: (l: 652, c: 25) - mutation from <class '_ast.NotEq'> to <class '_ast.Lt'>
 - ubelt/util_cache.py: (l: 652, c: 25) - mutation from <class '_ast.NotEq'> to <class '_ast.Gt'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.Sub'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.Add'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.Mod'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.FloorDiv'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.Div'>
 - ubelt/util_dict.py: (l: 168, c: 17) - mutation from <class '_ast.Mult'> to <class '_ast.Pow'>
 - ubelt/util_list.py: (l: 648, c: 18) - mutation from None to False
 - ubelt/util_list.py: (l: 648, c: 18) - mutation from None to True