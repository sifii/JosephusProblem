Name- Shifali Agrahari

Roll Number: 226201002

commands to be given to run programs on terminal
give input of n and k any interger
enter value of n: 10
enter value of k: 3

Implement Josephus Problem using list in PYTHON.

STEP 1- 
Take a input n, k from user 
  n be the number of persons standing in a circle facing the centre, 
  k be a skip number 

STEP 2-
create a list of alphabet according to given n
let n is 10 then list (A, B, C, D, E, F, G, H, I, J) name of list is (lst)

STEP 3 - 
A be the person who begins the process.
On each iteration, x will kill kth person on the left

STEP 4- 
BASE CONDITION- 
if n = 1,
then person A kills himself

CONDITION-
if k = 0 or n == k or k is multiple of n
then everyone kills himself

if k>n
then take a mod value of k
k = k%n

STEP 5 -
 x begins with A and is reset to be the person on the left of the person killed each time.
if n =10 (A, B, C, D, E, F, G, H, I, J) and k=3, 
INPUT - n = 10
        k = 3
OUTPUT - 
A kills D
E kills H
I kills B
C kills G
I kills C
E kills J
A kills I
A kills A
E kills F
E kills E

Your program will accept n and k as input from the user.
Output the order of execution till the program terminates