speech = """
Long years ago we made a tryst with destiny, and now the time comes when we shall 
redeem our pledge, not wholly or in full measure, but very substantially. 
At the stroke of the midnight hour, when the world sleeps, India will awake to life and freedom.
"""
target_word = input("Enter the word you want to count: ")
cleaned_speech = speech.lower()
word_count = cleaned_speech.count(target_word.lower())
print(f"The word '{target_word}' appears {word_count} times!")
# timetable-
