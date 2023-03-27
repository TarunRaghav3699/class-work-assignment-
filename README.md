# class-work-assignment-

para = input("Enter a paragraph: ")

# To find the number of sentences in the given string
sentence = 0
for i in para:
    if i == ".":
        sentence+=1
print(f"number of sentences are {sentence}")


# To find the number of word in the string 
alpha = 0
for i in para:
    if i ==" ":
        alpha+=1
print(f"number of words are {alpha + 1}")

# number of  vowels in the given paragraph
vowels = ["a","e","i","o","u"]
vowel=0
for i in para:
    if i in vowels:
        vowel+=1
print(f'number of vowels are {vowel}')


# number of stop words in the given paragraph
stopwords = ["is","am","are","we","have","had","your","you","my","me",]
word = 0
for i in stopwords:
    if i in para:
        word+=1
print(f"number of stopwords are {word}")
    
# number of characters in the given paragraph
char = 0
for i in para:
    if para[::] in para:
        if para[::]==" ":
            continue
        else:
            char+=1
print(char)
   
