Cyber Activity Risk Analyzer

This project is a Python program that analyzes student login activity scores to detect different levels of risk. It helps in identifying whether an activity is Low, Medium, High, or Critical risk based on the score entered by the user.

 How It Works:

First, the user enters their registration number. The program extracts the last digit (D) from it, which is used to apply personalized filtering logic.

Next, the user enters multiple activity scores. The program checks each score using a loop:

Negative values are ignored.

0–30 are categorized as Low Risk.

31–60 are categorized as Medium Risk.

61–100 are categorized as High Risk.

Above 100 are categorized as Critical Risk.

After categorizing all valid scores, the program applies personalization:

If D is even, all Low Risk scores are removed.

If D is odd, all Critical Risk scores are removed.

Finally, the program displays the filtered risk lists along with the total number of valid entries, ignored entries, and the number of scores removed due to personalization.

What I Learned:

Through this project, I improved my understanding of lists, loops, conditional statements, data validation, and how to apply personalized logic in Python programs.


