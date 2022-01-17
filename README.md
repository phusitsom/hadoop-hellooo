# THIS IS MY FIRST EVER HADOOP PROJECT (WordCount)

Simple implementation of Word-Count example.

# Usage
```
yarn jar ./wordcount.jar WordCount {INPUT_FILES} {OUTPUT_DIRECTORY}
```

# Example
```
yarn jar ./wordcount.jar WordCount /inputs/* /outputs/wordcount_output_dir004
```
## Input
```
Japanese Man Covered in Water Purposely Electrocutes Self in Police Box
January 16, 202230 Commentsby Rift


A seemingly emotionally distraught Japanese man was apprehended by police after he charged into a police box covered in water and reached for the electrical socket to commit suicide, with there currently being no explanation behind his hazardous actions.

Taking place at one in the morning on the 11th, the accused 32-year-old male company employee from Higashi-Osaka City entered the police box in Osaka’s Yao City, poured four liters of water on himself and then proceeded to plug an electrical cord into an outlet, electrocuting himself.

The unhappy man’s stunt caused a power outage and he was quickly captured by police officers, with there being three in the box at the time, who then charged him with trespassing and property damage.

Police suspect he was trying to commit suicide by electrocution, as the culprit also claimed he wanted to die; granted, some might label this incident as a cry for attention as such a method of suicide can typically be achieved in the standard home.
```

## Output
```
11th,	1
16,	1
202230	1
32-year-old	1
A	1
Box	1
City	1
City,	1
Commentsby	1
Covered	1
Electrocutes	1
Higashi-Osaka	1
January	1
Japanese	2
Man	1
Osaka’s	1
Police	2
Purposely	1
Rift	1
Self	1
Taking	1
The	1
Water	1
Yao	1
a	4
accused	1
achieved	1
actions.	1
after	1
also	1
an	2
and	4
apprehended	1
as	3
at	2
attention	1
be	1
behind	1
being	2
box	3
by	3
can	1
captured	1
caused	1
charged	2
claimed	1
commit	2
company	1
cord	1
covered	1
cry	1
culprit	1
currently	1
damage.	1
die;	1
distraught	1
electrical	2
electrocuting	1
electrocution,	1
emotionally	1
employee	1
entered	1
explanation	1
for	2
four	1
from	1
granted,	1
hazardous	1
he	4
him	1
himself	1
himself.	1
his	1
home.	1
in	7
incident	1
into	2
label	1
liters	1
male	1
man	1
man’s	1
method	1
might	1
morning	1
no	1
of	2
officers,	1
on	2
one	1
outage	1
outlet,	1
place	1
plug	1
police	4
poured	1
power	1
proceeded	1
property	1
quickly	1
reached	1
seemingly	1
socket	1
some	1
standard	1
stunt	1
such	1
suicide	2
suicide,	1
suspect	1
the	9
then	2
there	2
this	1
three	1
time,	1
to	4
trespassing	1
trying	1
typically	1
unhappy	1
wanted	1
was	3
water	2
who	1
with	3
```