# Zuriteam assignment-week 2

[By Jennifer Agbo]

[Anagram]

[This explains anargram game]

# Check if two words are anagrams
# Example:
# find_anagrams("hello", "check") --> False
# find_anagrams("below", "elbow") --> True


def find_anagram(word, anagram):
    # [assignment] Add your code here

    #Know the length of the string
    if (len(word) == len(anagram)):

        #sort the strings that will be inputted
        if (sorted(word) == sorted(anagram)):
            print(f"{first_word} and {second_word} are anagram")
        else:
            print(f"{first_word} and {second_word} are not anagram")
    else:
        print(f"{first_word} and {second_word} are not anagram")

        return True

#Ask the user for words and store them.

first_word = input("Enter a word: ").lower()
second_word = input("Enter a word: ").lower()

#print out the inputs
print("string value 1: ", first_word)
print("String Value 2: ", second_word)

find_anagram(first_word, second_word)



[The link](https://replit.com/@JenniferAgbo/ANAGRAM-GAME#main.py)

