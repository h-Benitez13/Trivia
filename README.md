# Trivia

So I did the theme of finishing the song lyric.
Unfortunately, I only had time to focus on three questions. 

As soon as the page loads, the background image of a microphone, label image "sing" and the start button are presented for the user.

Once the start button is clicked, here is what happens to the game:

1. Start Button and image, disappear.
2. First question is presented
    a. the options/choices are hover buttons, as the user moves their mouse over the option it changes color.

3. If the user answered correctly, their score increased by one (not in view)
4. The question and options fade, gif w/ text displays (briefly) 
5. Follow up question appears.

**regardless whether the answer was correct or not, the transition is the same
** GIF image and text displayed (briefly) then fades and a new question fades in . 
6. If the user guesses the question incorrectly, the incorrect score increases by one.
7. At the end of the game, the scoresheet appears with user tally
    a. correct answers
    b. incorrect answers
    c. questions did not answered (if ran out of time)

8. The restart button fades in 
9. Restart Button clicks, the game returns to the first page w/ the image and start button.
10. HOPE YOU ENJOY!!

*disclaimers*

I had trouble with the timer function. I could not figure out where to place the time function so that
it would be a set time for each question. So my timer is one long time function for the entirety of the game.

Reset button: the button is/was clickable, but I set the click.function() to the startGame() function and
it did not restart as I wanted it to. I understand how the program is read but could not figure how to fix it. 