1. text = "Programming"
reversed_text = text[::-1]
print("Reversed string:", reversed_text)




2. full_name = input("Enter your full name: ")
initials = ".".join([name[0].upper() for name in full_name.split()]) + "."
print("Initials:", initials)



3. text = input("Enter a string: ")
if text == text[::-1]:
    print("It's a palindrome.")
else:
    print("It's not a palindrome.")



4. sentence = input("Enter a sentence: ")
words = sentence.split()
print("Number of words:", len(words))




5. text = "This is a string and it is an example."
modified_text = text.replace("is", "was")
print("Modified string:", modified_text)
