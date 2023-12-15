--Quine McCluskey Read Me File-- 


For the program to function well, the user must provide input accordingly,
to what is being asked.


First will be the number of variables to be used.The user must provide an 
input which is within 1–26. Providing any inputs outside of this 
range would result in errors.


The second input that the user will give will be "Minterms." The limit for
The minimum terms that can be used will be changed according to the selected
number of variable. Make sure that there will be no repetition in the given 
minterms.


The third and last input that the user will provide will be the values for
the "don't care" Just like in the short term, its range also varies depending
on the number of variables to be used.


Note:Make sure that there will be no same values inputted in the "Minterms"
and "Don't Care", doing so would result in an inaccurate final answer.


Once finished providing these three inputs, the program will then proceed solving the given.


Step 1:
The given "Minterms" and "Don't Care" values, which are in decimal form, 
willbe converted into its respective binary representation.


Step 2:All of the items given will be arranged ascendingly based on the 
number of 1's present.on its binary representation
.

Step 3:After grouping the binary's with respect to its 1's, it will then 
compare allthe binary values. If there is a single-bit difference, the 
program will replacethis with a dash, "-". Otherwise, it will store the 
unmarked values in a different list.


Step 4 and Step 5:
For steps 4 and 5, it is just the same process as step 3. However, these 
stepsmay be skipped once there are no longer binary values that can be 
compared witheach other. 



Step 6 (Final Tabulation):
In this step, it would collect all the simplified 
binary representations together.with the binary representations that were 
not used. Then it would put an "/" tothe possible values of the binary representations. 
The values with "/" andalone in a column will be labeled as prime implicants. The prime 
implicantswill be the final answer.


Step 7:
Here, it simply converts all the prime implicants to their respective Boolean representation. 
If the value is "0," then it will be considered a NOT representation, while "1" is simply the 
same.