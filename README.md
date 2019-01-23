# Push Swap
Not finished yet

## Grade
Not graded yet

## Instructions

| instructions  | Description   |
|:-------------:|---------------|
| sa            | swap first two elements of stack A |
| sb            | swap first two elements of stack B |
| ss            | sa and sb at the same time |
| pa            | pops the first elememt on B and puts it on top of A |
| pb            | pops the first elememt on A and puts it on top of B |
| ra            | rotates stuck A up by one|
| rb            | rotates stuck B up by one |
| rr            | rotates both A and B up by one |
| rra           | rotates stuck A down by one |
| rrb           | rotates stuck B down by one |
| rrr           | rotates both A and B down by one |

## Usage

1. Run Make to compile
```
make
```

2. Run the program 
```
./push_swap [insert some numbers to sort]
```
or create a var "ARG" and use ruby to display
```
ARG=`ruby -e "puts (-540..539).to_a.shuffle.join(' ')"``; ./push_swap $ARG | ./checker -v $ARG
```
* **ruby must be installed**

## More about the project

[Check the subject file](https://github.com/thaisavelino/push-swap/blob/master/about-project/push_swap.en.pdf)
