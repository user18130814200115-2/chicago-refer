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

## Contributions
Conntributions and issues are extremely welcome.
References are often complex and if my system has any holes in it, please feel free to either fix them and make a PR or submit an issue.
