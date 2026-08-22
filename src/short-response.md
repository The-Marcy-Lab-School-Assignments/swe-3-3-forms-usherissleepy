# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Accessibility means designing websites so that people with different abilities can still use and understand them. Labels help by telling users what each input is for and by allowing screen readers to describe the input correctly. They also make the label clickable, which can make it easier to select or focus the input.**

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**The for attribute goes on a <label> and connects that label to an input by matching the input's id. The id uniquely identifies an element on the page and is also used for things like labels, CSS, and JavaScript. The name attribute is used when form data is submitted because it becomes the key associated with the user's input value.**

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Specific input types tell the browser what kind of data the user is supposed to enter. For example, type="email" can check for a valid email format, and type="number" can limit the input to numbers. They also improve the user experience by showing more appropriate keyboards and built-in validation.**

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**A real example is a login form on a website like Instagram. The user enters their username or email and password, and the form sends that data to the server. The server checks whether the information matches an account and then either logs the user in or returns an error message.**
