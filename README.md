# MultiplicativePersistence

Multiplicative Persistence Search Program

This Python program searches for a number with a specific multiplicative persistence, particularly a persistence of 12. The program is optimized to prioritize numbers that start with smaller digits like 2 or 3, followed by higher-value digits like 7, 8, and 9, which are more likely to produce high multiplicative persistence.

What is Multiplicative Persistence?

Multiplicative persistence of a number is the number of times you must multiply the digits of the number together until you get a single digit. For example:

	•	The multiplicative persistence of 39 is 3 because:
	•	3 * 9 = 27
	•	2 * 7 = 14
	•	1 * 4 = 4 (single digit)

Program Details

Features

	•	Digit Filtering: The program skips numbers containing the digits 0, 4, or 5 since these are less likely to contribute to high multiplicative persistence.
	•	Priority Search: It prioritizes numbers starting with 2 or 3, followed by digits 7, 8, or 9, which are more likely to lead to high persistence.
	•	Verbose Output: The program prints each number it checks, allowing you to monitor its progress.

How It Works

	1.	The program starts at 1 and increments, checking each number to see if it has the desired multiplicative persistence.
	2.	It skips numbers containing the digits 0, 4, or 5.
	3.	It checks if the number starts with 2 or 3 and contains only digits from the set 2, 3, 7, 8, 9.
	4.	Once a number with the specified multiplicative persistence is found, it prints the result and terminates.

Usage

To use the program, simply run the Python script. You can modify the target multiplicative persistence by changing the target_persistence variable.
Customization

	•	Change Starting Digits: You can modify the has_desirable_starting_digits function to change the digits the program prioritizes.
	•	Target Persistence: Adjust the target_persistence variable to search for numbers with different levels of multiplicative persistence.

Notes

	•	Performance: Finding a number with high multiplicative persistence can take time due to the rarity of such numbers. The program is optimized to skip non-promising numbers, but large search spaces still require computational resources.

License

This project is open-source and available under the MIT License.
