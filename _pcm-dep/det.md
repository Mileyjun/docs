---
layout: relation
title: 'det'
shortdef: 'determiner'
udver: '2'
---

The `det` relation is used between a nominal phrase and its determiner.

~~~ conllu
# visual-style 2 1 det	color:blue
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
1	dis	_	DET	_	_	2	det	_	_
2	thing	_	NOUN	_	_	4	nsubj	_	_
3	no	_	PART	_	_	4	advmod	_	_
4	good	_	ADJ	_	_	0	root	_	_

1	this	_	_	_	_	0	_	_	_
2	thing	_	_	_	_	0	_	_	_
3	not	_	_	_	_	0	_	_	_
4	good	_	_	_	_	0	_	_	_

1	This	_	_	_	_	0	_	_	_
2	thing	_	_	_	_	0	_	_	_
3	is	_	_	_	_	0	_	_	_
4	not	_	_	_	_	0	_	_	_
5	good	_	_	_	_	0	_	_	_

~~~