## Class 4 Reading notes React and forms

What is a ‘Controlled Component’?
A controlled component in React is a form element whose value is controlled by React state. 

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. It's  better to update the state with the user's responses as soon as they enter them. This allows real-time validation and feedback to the user as they are filling out the form, which can lead to a better user experience. Waiting until the form is submitted to store the user's responses in state can make it more difficult to provide feedback and can lead to a slower user experience.

How do we target what the user is entering if we have an event handler on an input field?
In the event handler for an input field, you can access the value of the input field using the event object.

Why would we use a ternary operator?
A ternary operator is a way of writing an if-else statement. We use a ternary operator when we want to conditionally render content based on a certain condition. It allows us to write more clear and readable code.

Rewrite the following statement using a ternary statement:
message = loggedIn ? 'Welcome back!' : 'Please log in.';

## Things I would like to know more about