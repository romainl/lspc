# lspc

Ideally, an LSP client should make use of Vim's built-ins as much as possible.

Feature                    |Mandatory|Vim built-in
---------------------------|---------|---
completion                 |yes      |completion
hover                      |yes      |ballooneval
go to definition           |yes      |tags via a temp tags file? gd?
find references            |yes      |?
document symbols           |yes      |?
diagnostics                |yes      |makeprg, :make, quickfix
signature help             |no       |:ptag, etc.
go to type definition      |no       |?
go to implementation       |no       |?
document highlights        |no       |?
code actions               |no       |maybe a prompt?
code lens                  |no       |?
document link              |no       |gx or gf?
document color             |no       |?
color presentation         |no       |?
document formatting        |no       |formatprg and gq
document range formatting  |no       |idem
document on type formatting|no       |idem + formatoptions
rename                     |no       |search > qf > cdo/cfdo
prepare rename             |no       |?
folding                    |no       |foldexpr
