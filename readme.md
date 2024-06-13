to add auto completing support for i_ctrl-x_ctrl-f

## what it does
* it overrides the original i_ctrl-x_ctrl-f
* provides auto completion after pressed `<c-x><c-o>`
* stops itself at InsertLeavePre automatically
* and treats `i_/` specially

## status
* just works
* feature complete

## prerequisites
* haolian9/infra.nvim

## usage

my personal config:
```
m.i("<c-x><c-f>", function() require("icxcf")() end)
```
