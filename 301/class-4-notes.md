# React and Forms

__What is a ‘Controlled Component’?__

A Controlled Component is a form element. React pulls string instead of letting the user directly change its value. Holds onto value in its own state.

__Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.__

We should update the state with the user's esponses as soon as they enter them because it provides a better user experience. By updating the state as soon as they type, we can keep track of what they're saying in real time. This helps us react faster and give feedback instantly.

__How do we target what the user is entering if we have an event handler on an input field?__

When the user types something itno the input field, we can know what they typed by using a function called 'event handler'. This function listens for changes in the input field. When there's a change, it grabs whatever the user typed and stores it in a place called state.

__Why would we use a ternary operator?__

We would use a ternary operator when we want to make decisions in our code in a short and simple way. Shortcut for 'if else' statement.

__Rewrite the following statement using a ternary statement:__

console.log( x === y ? true : false);
