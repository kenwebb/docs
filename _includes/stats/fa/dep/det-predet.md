

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is a language-specific subtype of [det]().

54 nodes (0%) are attached to their parents as `det:predet`.

54 instances of `det:predet` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.01851851851852.

The following 4 pairs of parts of speech are connected with `det:predet`: [fa-pos/NOUN]()-[fa-pos/DET]() (36; 67% instances), [fa-pos/NOUN]()-[fa-pos/ADV]() (9; 17% instances), [fa-pos/NOUN]()-[fa-pos/PRON]() (7; 13% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (2; 4% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 det:predet	color:blue
1	از	از	ADP	P	_	4	case	_	_
2	سراسر	سراسر	DET	DET	_	4	det:predet	_	_
3	این	این	DET	DET	_	4	det	_	_
4	سرزمین	سرزمین	NOUN	N_SING	Number=Sing	10	nmod	_	_
5	بوی	بوی	NOUN	N_SING	Number=Sing	10	nsubj	_	_
6	عشق	عشق	NOUN	N_SING	Number=Sing	5	nmod:poss	_	_
7	و	و	CONJ	CON	_	6	cc	_	_
8	لطف	لطف	NOUN	N_SING	Number=Sing	6	conj	_	_
9	بر	بر	ADP	PREV	_	10	compound:prt	_	_
10	می‌خیزد	خاست#خیز	VERB	V_PRS	Number=Sing|Person=3|Tense=Pres	0	root	_	_
11	.	.	PUNCT	DELM	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 det:predet	color:blue
1	وی	وی	PRON	PRO	Number=Sing|Person=3|PronType=Prs	12	nsubj	_	_
2	که	که	SCONJ	CON	_	7	mark	_	_
3	هیچ	هیچ	ADV	ADV_NEG	Negative=Neg	5	det:predet	_	_
4	گونه	گونه	NOUN	N_SING	Number=Sing	5	det	_	_
5	سلاحی	سلاح	NOUN	N_SING	Number=Sing	7	dobj	_	_
6	حمل	حمل	NOUN	N_SING	Number=Sing	7	compound:lvc	_	_
7	نمی‌کرد	_	VERB	V_PA	Number=Sing|Person=3|Tense=Past	1	acl:relcl	_	_
8	،	،	PUNCT	DELM	_	12	punct	_	_
9	توسط	توسط	ADP	P	_	10	case	_	_
10	پلیس	پلیس	NOUN	N_SING	Number=Sing	12	nmod	_	_
11	بروکسل	_	NOUN	N_SING	Number=Sing	10	nmod:poss	_	_
12	دستگیر	دستگیر	ADJ	ADJ	Degree=Pos	0	root	_	_
13	شد	کرد#کن	VERB	V_PA	Number=Sing|Person=3|Tense=Past	12	cop	_	_
14	.	.	PUNCT	DELM	_	12	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 det:predet	color:blue
1	علاوه	علاوه	ADP	P	_	3	case	_	_
2	بر	بر	ADP	P	_	1	mwe	_	_
3	آن	آن	PRON	PRO	Number=Sing|PronType=Dem	14	nmod	_	_
4	همه	همه	PRON	PRO	PronType=Tot	6	det:predet	_	_
5	این	این	DET	DET	_	6	det	_	_
6	رفتار	رفتار	NOUN	N_SING	Number=Sing	14	dobj	_	_
7	و	و	CONJ	CON	_	6	cc	_	_
8	شیوه	شیوه	NOUN	N_SING	Number=Sing	6	conj	_	_
9	را	را	PART	CLITIC	_	6	case	_	_
10	نیز	نیز	SCONJ	CON	_	14	advmod	_	_
11	عین	عین	ADV	ADV_COMP	_	12	case	_	_
12	دین	دین	NOUN	N_SING	Number=Sing	14	nmod	_	_
13	معرفی	معرفی	NOUN	N_SING	Number=Sing	14	compound:lvc	_	_
14	می‌کرد	کرد#کن	VERB	V_PA	Number=Sing|Person=3|Tense=Past	0	root	_	_
15	.	.	PUNCT	DELM	_	14	punct	_	_

~~~


