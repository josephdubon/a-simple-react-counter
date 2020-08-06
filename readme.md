# React A Simple Counter

Assignment

    If you haven't yet built the counter, do it now.
    Prevent the counter from going below 0.
    Prevent the counter from going above 20.

## GitLab Pages URL

<https://josephdubon.gitlab.io/a-simple-react-counter>

### Assessment Development Plan / From Video Lesson

Are you starting to get a feel for React? I think it's time to try some stuff on your own.

    If you haven't yet built the counter, do it now.

First, if you didn't build the counter along with me, go ahead and see if you can get it working, with both increment and decrement buttons.

    Prevent the counter from going below 0.
    Prevent the counter from going above 20.

Once you have that much working, see if you can modify the app to prevent the counter from going below 0. Right now, you can just keep bashing the decrement button, and it will keep right on decrementing. Let's put an end to that.

Once you've established a minimum value, why not set a maximum? Let's keep it from going above 20. These two exercises are really just JavaScript. It's important to remember that at the end of the day, React is just JavaScript, so you can often tackle problems the same way you would if React weren't involved.

    Turn the counter red when it's 10 or higher.
    Change it back to the original color if it goes below 10.

If you can handle that much, why not push yourself a little harder? See if you can turn the counter red when the number is 10 or higher. We haven't talked about styling components, so you'll need to read up on this on your own. Check out the link in the notes.

Oh, and while you're at it, you may as well change it back to the original color if it goes below 10 again. All right. Ready for more?

    Allow the initial count to be set from a prop.
    If an initial count is not passed in, the count should start at 0.

Right now, we always start the count at zero. Why don't we allow the initial count to be passed in as a prop?

If no such prop is passed in, we should still start the count at zero. This is definitely testing our understanding of React now. Ready for a little more?

    Add a button to reset the counter.
    Only show this button if the counter has been modified from its original state.

Try adding a button to reset the counter back to its initial value—either whatever was passed in via the prop from the previous step, or zero if nothing was passed in.

And you know what? Only show this button if the counter has been modified from its original state. If it's never changed, there's no sense in showing the reset button, is there? See if you can figure that out.

#### How to Break Down a Project

1. Read the requirements document in detail.
   a. Take notes of important points.
   b. Write down your questions.
2. Answer your questions!
3. Make a development plan.
   a. Describe the entire behavior of the program in 3 (or at most 4) steps. Don't use any JavaScript words!
   b. Break down each item into 4 (or 4) smaller steps by asking the question, "How?".
   c. Repeat until it's obvious how to turn the step into JS code.
4. Write the code!
