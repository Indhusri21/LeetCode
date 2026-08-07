# DAY 1
    PROBLEM TITLE: TWO SUM
    PROBLEM EXPLANATION:
        This solution uses a nested loop approach to check every possible pair of elements in the array:
            >>Outer Loop (`i`): Iterates through each element from index `0` to `n-1`.
            >>Inner Loop (`j`): Iterates through subsequent elements starting from index `i + 1` to avoid checking the same pair or using an element twice.
            >>Check Sum: Checks if `nums[i] + nums[j] == target`. If true, returns `[i, j]`.

----------------------------------------------------------------------------------------------------
# DAY 2
    PROBLEM TITLE:REVERSE STRING
    PROBLEM EXPLANATION:
            >>Solved using python lists built-in function > .reverse()
 ---------------------------------------------------------------------------------------------------
 # DAY 3
    PROBLEM TITLE:FIZZ BUZZ
    PROBLEM EXPLANATION:
            >>Initialized an empty list.
            >>Loop form 1 to n+1.
            >>Used if elif and else for Fizzbuzz condition.
                APPENDS
                    ~FizzBuzz if i%3==0 and i%5==0
                    ~Fizz if only i%3==0
                    ~Buzz if only i%5==0
                    ~Else Number itself 
            >>Appended the result to empty list and displayed.         
---------------------------------------------------------------------------------------------------
# DAY 4
    PROBLEM TITLE:Reverse Words in a String
    PROBLEM EXPLANATION:
            >>Split the string using .split()
            >>Using slicing method reversed the string and joined and displayed the reversed string.
----------------------------------------------------------------------------------------------------

# DAY 5
    PROBLEM TITLE:ADD BINARY
    PROBLEM EXPALNATION:
            >>Adding two binary strings by specifing it as int and '+' operator is used.
            >>The specification 'int(a,2)' will allows to read the number as binary if ',2' is not specified the number will read as decimal.
            >>Using [2:] is used for doesnt considering first two numbers.
            >>Using 'bin()' the addition result is returned as binary.
----------------------------------------------------------------------------------------------------

# DAY 6
    PROBLEM TITLE:ROMAN TO INTEGERS
    PROBLEM EXPLANATION:
            >>Mapping each Roman letter (I, V, X, L, C, D, M) to its number value.
            >>Finding length and initializing total = 0.
            >>Reading the Roman numeral from left to right, comparing each letter to the next one.
            >>If a letter is smaller than the next letter, subtract its value from the total.
            >>Otherwise (if it is larger or equal), add its value to the total.
            >>Returning the integer of the roman numerals.

----------------------------------------------------------------------------------------------

# DAY 7
    PROBLEM TITLE:TO LOWERCASE
    PROBLEM EXPLANATION:
            >>Reversed the string using .lower() and displayed it.

----------------------------------------------------------------------------------------------
# DAY 8
    PROBLEM TITLE: REVERSE WORDS OF THE STRING
    PROBLEM EXPLANATION:
            >>Split the words in the string seperately using .split().
            >>Reversed the words seperately and rejoined them as string.
            >>Displayed the output string.
----------------------------------------------------------------------------------------------

# DAY 9
    PROBLEM TITLE: lENGTH OF LAST WORD
    PROBLEM EXPLANATION:
            >>.strip helps to remove spaces and split helps to separate the words in the string.
            >>using indexing finding the length of last word.
            >>Displayed the output string.

----------------------------------------------------------------------------------------------

# Day 10
    PROBLEM TITLE: CONVERT A NUMBER TO HEXADECIMAL
    PROBLEM EXPLANATION:
            >>Converting the negative numbers to hexadecimal number.
            >>Using built-in hex() to convert positive integers to hexadecimal.
            >>Displaying the output.

----------------------------------------------------------------------------------------------
# DAY 11
    PROBLEM TITLE: FIND THE INDEX OF FIRST OCCURENCE IN A STRING
    PROBLEM EXPLANATION:
            >>Check length: Return -1 immediately if needle is longer than haystack.
            >>Slide window: Move a fixed-size window across haystack one character at a time.
            >>Compare text: Check if the substring inside the current window equals needle.
            >>Return result: Return the starting index on the first match, or -1 if never found.

------------------------------------------------------------------------------------------------

# DAY 12
    PROBLEM TITLE: BASE 7
    PROBLEM EXPLANATION:
            >>Solved using numpy.
            >>Return "0" immediately if num is 0.
            >>Save the negative sign if num < 0, then work with abs(num)[abs gives absolute value]
            >>Repeatedly divide the number by 7, collecting the remainders for each digit.
            >>Reverse the collected digits and prepending the stored sign.

------------------------------------------------------------------------------------------------
# DAY 13
    PROBLEM TITLE: VALID PALINDROME
    PROBLEM EXPLANATION:
            >>Joining the sentence without symbols and converting all in lower case.
            >>Checking if the sentence is palindrome by the condition word = word[::-1], if it is palindrome it returns true otherwise false.

----------------------------------------------------------------------------------------------------