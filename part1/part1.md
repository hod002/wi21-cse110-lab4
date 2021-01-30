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

14. 

15.

16.

17.

18.

19.

20.

21.

