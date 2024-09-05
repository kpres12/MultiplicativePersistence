# MultiplicativePersistence

Multiplicative Persistence Search Program

This Python program is designed to find the smallest number with a specific multiplicative persistence, which is the number of steps required to reduce a number to a single digit by repeatedly multiplying its digits.

Features

	1.	Digit Filtering: The program skips numbers containing digits that typically lower multiplicative persistence (0, 1, 4, and 5).
	2.	Priority Search: Numbers starting with 2 or 3 are prioritized, as they are more likely to yield higher multiplicative persistence.
	3.	Avoiding Permutations: The program avoids redundant checks by skipping different permutations of the same digit combination.
	4.	Combinatorial Generation: The program generates and checks numbers with desirable digits first, improving the efficiency of the search.

How to Use

	1.	Set the Target Persistence: Modify the target_persistence variable in the script to the desired persistence level (for example, n).
	2.	Run the Program: Execute the script in a Python environment. The program will print out each number it checks and its corresponding persistence.
	3.	View Results: Once the program finds a number with the specified persistence, it will output the smallest such number.

Customization

	•	Change the Target Persistence: Adjust the target_persistence variable to search for numbers with different levels of multiplicative persistence.
	•	Set Maximum Digit Length: Optionally, you can set a maximum digit length to limit the search space, which can help improve performance.

Notes

	•	Performance: Searching for high multiplicative persistence numbers can be computationally intensive. The program is optimized but may still require significant computational resources for large searches.
	•	Mathematical Context: The search for numbers with very high multiplicative persistence is a 

License

This project is open-source and available under the MIT License.
