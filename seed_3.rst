Mutatest diagnostic summary
===========================
 - Source location: /home/sam/Desktop/cs182/project/ubelt/ubelt
 - Test commands: ['pytest']
 - Mode: s
 - Excluded files: []
 - N locations input: 10
 - Random seed: 3

Random sample details
---------------------
 - Total locations mutated: 10
 - Total locations identified: 1670
 - Location sample coverage: 0.60 %


Running time details
--------------------
 - Clean trial 1 run time: 0:00:03.465319
 - Clean trial 2 run time: 0:00:03.966019
 - Mutation trials total run time: 0:01:27.473511

Overall mutation trial summary
==============================
 - DETECTED: 18
 - SURVIVED: 5
 - TOTAL RUNS: 23
 - RUN DATETIME: 2020-03-09 16:28:15.297843


Mutations by result status
==========================


SURVIVED
--------
 - ubelt/_win32_links.py: (l: 502, c: 58) - mutation from None to True
 - ubelt/progiter.py: (l: 349, c: 8) - mutation from If_Statement to If_True
 - ubelt/util_arg.py: (l: 64, c: 19) - mutation from <class '_ast.Lt'> to <class '_ast.NotEq'>
 - ubelt/util_import.py: (l: 358, c: 23) - mutation from False to None
 - ubelt/util_import.py: (l: 464, c: 7) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>


DETECTED
--------
 - ubelt/util_arg.py: (l: 64, c: 19) - mutation from <class '_ast.Lt'> to <class '_ast.Gt'>
 - ubelt/util_arg.py: (l: 64, c: 19) - mutation from <class '_ast.Lt'> to <class '_ast.LtE'>
 - ubelt/util_arg.py: (l: 64, c: 19) - mutation from <class '_ast.Lt'> to <class '_ast.Eq'>
 - ubelt/util_arg.py: (l: 64, c: 19) - mutation from <class '_ast.Lt'> to <class '_ast.GtE'>
 - ubelt/util_dict.py: (l: 328, c: 7) - mutation from <class '_ast.Is'> to <class '_ast.IsNot'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.Mod'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.FloorDiv'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.Mult'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.Div'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.Sub'>
 - ubelt/util_format.py: (l: 624, c: 57) - mutation from <class '_ast.Add'> to <class '_ast.Pow'>
 - ubelt/util_hash.py: (l: 461, c: 12) - mutation from If_Statement to If_False
 - ubelt/util_hash.py: (l: 461, c: 12) - mutation from If_Statement to If_True
 - ubelt/util_import.py: (l: 217, c: 29) - mutation from Index_NumNeg to Index_NumZero
 - ubelt/util_import.py: (l: 217, c: 29) - mutation from Index_NumNeg to Index_NumPos
 - ubelt/util_import.py: (l: 358, c: 23) - mutation from False to True
 - ubelt/util_import.py: (l: 683, c: 44) - mutation from None to False
 - ubelt/util_import.py: (l: 683, c: 44) - mutation from None to True