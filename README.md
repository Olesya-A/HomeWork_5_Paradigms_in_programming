% Rules \
sum_list([X], X). \
sum_list([X|T], Sum) :- \
sum_list(T, Sum1), \
Sum is Sum1 + X. \
 \
% Query \
sum_list([1,2,3,4,5,6,7,8,9,10],Sum) \
