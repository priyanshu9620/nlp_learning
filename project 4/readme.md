Dog vs cat classification using CNN 

training acc=97%
testing acc=80%

you can improve acc using 
1. batch norm
2. l1/l2 reg
3. dropouts
(i have commented them implement seperately and compare accuracy)

after transfer learning 

1. without augumentation and just using transfer learning with imagenet dataset : acc->90%
2. with augumentation and tranfer learning : acc->91.4%
3. with transfer learning using fine tunning : acc->95.2%
(first 2 are transfer learning with feature extraction method)
