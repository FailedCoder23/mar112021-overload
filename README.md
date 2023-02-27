## mar112021-overload
this is an archive of iready overload, the original one
# iReady-Overload
iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't even try to make their product enjoyable, or even acceptable, for an hour and a half every single week. This code is designed to rid people of this torment and will allow to skip through iready lessons and get 100% score on all quizzes. Because of the way iReady works, it will have to leave one lesson segment (usually 10-30 seconds) or one quiz question, but the quiz will always result in a score of 100%.

# How to use
Simply open an iReady lesson, use ctrl + shift + i or "inspect element" to open developer tools, click on "console" and paste the code from lesson.js into the console and hit enter. Then, wait a second, click the "x" on the top right of the lesson to go the menu, and paste external.js in the console while on the menu.

Note that so far, it only works on math lessons and quizzes, not reading.

If you see an error saying Uncaught (in promise) SyntaxError: Unexpected end of JSON input, then just close the lesson and try again.

# Failsafe
If something goes wrong and your lesson stops working, first try refreshing and opening the lesson again. If that doesn't work, open the iReady lesson/quiz, use ctrl + shift + i or "inspect element" to open developer tools, click on "console" and paste the code from resetLesson.js into the console and hit enter. Then, wait a second, click the "x" on the top right of the lesson to go the menu, and paste external.js in the console while on the menu. This should reset the lesson or quiz to its original state.
