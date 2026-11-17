# aixcelerate-mood-guesser
...
# Mood Guesser

## Level 3: Testing
Accuracy on the 5 practice sentences: 100%

1. The sentence that was closest to going wrong was “Today was a great day.” Before I added “great” to my Happy clues, neither list matched, so both scores tied and the program chose Sad.
2. One change that could improve my program is One improvement would be to use more varied training sentences and test the program on examples it hasn’t seengive me tha sentence that shul.

## Learning questions

1. “good party today” total score and mood:+2 +1 +0 = +3, so Happy.
2. “bad exam day” total score and mood:+2 +1 +0 = +3, so Happy.
3. “exam” scored 0  I think this is good because it appears once in both Happy and Sad examples. That balances out; it can be useful because it avoids favoring either mood, though it gives no clue.
4. “not good” is labelled Happy because the method sees “good” (+2) but doesn’t understand that “not” reverses its meaning. It could account for negation words such as “not” near a clue.

## AI declaration
I used an AI tool: yes.
I asked ChatGPT to help me understand the project steps, choose clue words for the Happy and Sad lists, and explain and debug my Python code. I ran the code in Google Colab and checked its output. I reviewed and ran the code myself.

## Reflection
The hardest part for me was choosing clue words and understanding why the program made a wrong guess. I learned I learned that it only recognizes words in its clue lists, so adding a useful clue like “great” can change its prediction.


