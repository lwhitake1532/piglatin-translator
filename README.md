# piglatin-translator
def piglatin():
    words = input("input sentences: ").split()
    vowels = 'aeiou'
    
    for word in words:
        print(word[1:] + word[:1] + 'ay', end = ' ')

    if word in vowels:
        print(f"[word] is a vowel")
    else:
        print(f"[word] is not a vowel")
piglatin()
