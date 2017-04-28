# Interview Guidelines

Here are some general guidelines to consider when interviewing.

## Know what you know!
***All*** the things taught in class:
1. Arrays
2. For loops
3. Conditionals (and expressions!)
4. Click handlers
5. Jquery selectors and functions discussed in class (for example, `setInterval`)
6. Variable types (for example, `string`, `number`, `array`, `object`, etc)
7. Basic Javascript/CSS/HTML (linking to CSS file, linking to javascript file, HTML elements, etc)
8. Functions!

[warning] For best results, study for an interview like you would a test.

[warning] Do not be afraid to use programming skills you may have learned outside of Code2College.

## Talking with the Interviewer
1. Ask Questions: If there’s something missing or you need clarification on anything, don’t be afraid to ask questions during the interview.
2. Be Verbal: If an interviewer can hear your thoughts, they can help guide you down the right path. Don’t sit in silence thinking about your answer. Instead, talk it out.
3. Write away: Feel comfortable writing on paper/whiteboard even if you’ll be coding on a laptop. Especially since coding on the environment can be distracting b/c of the errors it may show. This also helps to display what you know
4. Back Track: If you lose your place, backtrack to identify where you are. But remember to do so out loud.
5. Be Confident: You know a lot, but won’t be expected to know everything. State what you know. Use what you know to figure out what you don’t.
6. Etiquette: Make eye contact with the Inteviewer when speaking or being spoken to.
7. Past projects: Be prepared to speak about any coding projects you have previously worked on. Things like what you liked about some of your past projects, what did you learn from them, what exactly made you excited about that project, etc, can help the interviewer get a sense of your interests and potentially where your skills are focused.

## Coding Etiquette while interviewing
1. Style matters more so than absolute correct-ness! This means that if the interviewer can't read your code, either on paper/whiteboard or on a computer, you are already behind! Think about how your code functions ***AND*** looks (ie. do you have the right spacing between brackets? Are you variables/functions appropriately named, etc)

For example:

***Good code***
```javascript
$(document).ready(function() {
    var headerText = "Old Header Text";

    $("#button1").click(function() {
        headerText = "New Header Text";
        // update text in header
        $("h1").html(headerText);
    });

    function updateBackgroundColor(newBackgroundColor) {
        $("h1").css("background-color", newBackgroundColor);
    }
});
```

_Sad Code_ :(
```javascript
$(document).ready(function() {
    var myvar = "Old Header Text";

    $("#button1").click(
        function() {
    myvar = "New Header Text";
        $("h1").html(myvar);});

function bgupdate(color) {
$("h1").css("background-color", newBackgroundColor);
}
});
```

2. Even with a computer, writing down code, if possible, can help. This allows you to demonstrate your thought process before committing code to the computer.

3. Solving the problem is better than not solving the problem. If you are struggling with a particular question, think about the simplest part of the problem you can solve and continue working in this way until you have solved the problem entirely.
    - Wait until after a problem is solved to review and find ways to improve the solution, as time allows.