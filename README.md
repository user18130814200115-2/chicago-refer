# chicago-refer
GNU refer macros for Groff using the Chicago author-date style.

This macro distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.

## Usage
`include` or cat the macro file with your groff file to use it.

I have only tested this with the `mom` macro set.

## Particularites
Currently, if you want a news article, you need a `%w` section in your bibliography file to indicate the paper.
This is because refer defaults to using `ref*spec 2` if an Issuer (`%I`) is set.

### Book reviews
Book reviews can be added with th `%r` and `%e` tags.  
`%r` is the reviewer while `%e` is the reviewed work.
A reviewer must be set, otherwise whole line will not be printed.

### Interviews
The Interviewr can be set with `%v`, Other (`%O`) should be set to "program,pulication,date,url"

### Thesis
To reference a thesis, set City (`%C`) to the departement and Issuer (`%I`) to the university.

### Social Media Content
For ocial media content, the Issuer 9(`%I`)can be set to the platform, and Other (`%O`) to the url.

## Contributions
Conntributions and issues are extremely welcome.
References are often complex and if my system has any holes in it, please feel free to either fix them and make a PR or submit an issue.

# LISENCE
This Macro set is free software, you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Includes code from the `mom` macros
Copyright (C) 2002-2018  Free Software Foundation, Inc.
 Written by Peter Schaffter <peter@schaffter.ca>
 PDF integration contributed by Deri James <deri.james@chuzzlewit.co.uk>
