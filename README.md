# chicago-refer
GNU refer macros for Groff using the Chicago author-date style.

This macro distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.

## Usage
You can use the `.so` primitive to include this file in yur groff documents.
You can also use [my groff module system](https://github.com/user18130814200115-2/groffscripts).

You will need to manually set the GNU refer settings, either from the comandline or with a
.R1/.R2 block.
You can output the reccomened block to the commandline with the call `.chicago`.
```
[chicago]: please manually add a refer block containing the following info:
.R1
label "(A.n|Q) ', ' (D.y|D)"
bracket-label " (" ")" ", "
join-authors ", and " ", " ", and "
move-punctuation
reverse A1
sort A1Q1T1B1E1
database [PATH_TO_DATABASE]
.R2
```

I have only tested this with the `mom` macro set.

# LISENCE
This Macro set is free software, you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Includes code from the `mom` macros
Copyright (C) 2002-2018  Free Software Foundation, Inc.
 Written by Peter Schaffter <peter@schaffter.ca>
 PDF integration contributed by Deri James <deri.james@chuzzlewit.co.uk>
