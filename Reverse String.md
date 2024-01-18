sentence=input()
def reverse(sentence):
    words=sentence.split(" ")
    new_word=[word[::-1] for word in words]
    rev=" ".join(new_word)
    return rev
print(reverse(sentence))
