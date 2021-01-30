# Part 1
1. It will print the value of i after the last loop (prices.length) because var is in same the function scope.

2. It will print the value of the discountedPrice from the last loop iteration (calculated with prices[prices.length - 1]) because var is\
in the same function scope.

3. It will print the value of finalPrice in the last iteration of the for loop because that is when it is last updated and it is\
within the same function scope.

4. It returns [50, 100, 150] because the for loop iterates through the prices and calculates the discounted price; \
then it rounds the price and pushes the new price to the end of the discounted array. The discounted array is returned after\
the loop terminates.

5. It will throw an error because i isn't defined in the block.

6. It will throw an error because discountedPrice is not defined in the block.

7. It will print the value of finalPrice in the last iteration of the for loop because finalPrice was declared before the\
for loop (same block as console.log()), so the any changes made to finalPrice in the for loop will be saved.

8. It returns [50, 100, 150] because the for loop iterates through the prices and calculates the discounted price; \
then it rounds the price and pushes the new price to the end of the discounted array. The discounted array is returned after\
the loop terminates.

9. It will throw an error because i isn't defined in the block.

10. It will throw an error because discountedPrice is not defined in the block.

11. It would print the value of finalPrice because it is defined in the same block as the console.log() call.

12. The function would throw an error because finalPrice and discounted are declared as const, and the for loop attempts to change\
their values. 

13. A) student.name B) student['Grad Year'] C) student.greeting() D) student['Favorite Teacher'].name E) student.courseLoad[0]

14. A) 32 because the '3' + indicates string concatentation. B) 1 because the "-" indicates subtraction so '3' is converted to int.\
C) 3 because null is converted to 0 for addition. D) 3null because null is converted to a string for concatentation. E) 4 because true\
is equal to 1. F) 0 because false is equal to 0 and this is addition, not string concatentation so null is 0. G) 3undefined because\
the "3" + indicates string concatentation so undefined is converted to a string. H) NaN because undefined is equal to NaN during\
arithmetic calculations and the "-" indicates subtraction and converts "3" to an int.

15. A) true because '2' is converted to a number. B) false because both are strings, indicating string comparison; '2' has a greater\
index than '1'. C) true because '2' is converted to a number. D) false because strict comparison checks types. E) false because true\
is equal to 1. F) true because Boolean(2) returns true.

16. == converts types before checking equality; === checks equality without type conversion.

17. "How are you?" because 2 is compared to true, which is equal to 1; this evaluates to false. The second comparison is just 2, which\
evaluates to true because any values other than zero, undefined, or null will evaluate to true. 

19. [6, 8, 10] because newArr pushes the return value of doSomething(array[i], function(x) {return x* 2;}) during each loop iteration.\
doSomething returns ((array[i] + 2) * 2) each iteration. The first value is (1 + 2) * 2 = 6; then, (2 + 2) * 2 = 8; then, (3 + 2) * 2\
= 10.

21. 1342

