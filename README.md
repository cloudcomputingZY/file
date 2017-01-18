flow 
st=>start: Start
io=>inputoutput: Inputoutput
op=>operation: opt
cond=>condition: yes or no
sub=>subroutine:your subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
