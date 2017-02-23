# no_repeats
New ways to avoid duplicate solutions


```prolog

:- pack_install('https://github.com/TeamSPoon/pack_no_repeats.git').

```


```prolog

?- use_module(library(no_repeats)).

?- no_repeats( X , member(X-Y,[3-2,1-4,1-5,2-1])).
% X = 3, Y = 2 ;
% X = 1, Y = 4 ;
% X = 2, Y = 1.


 ?- no_repeats(member(X,[3,1,1,1,3,2])).
% X = 3 ;
% X = 1 ;
% X = 2.


```



