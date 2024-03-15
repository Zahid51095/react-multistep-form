# Description:

This multi-step form application is built using React with TypeScript, providing type safety and improved developer experience. It enables users to create an account by furnishing their personal details, address information, and account credentials.
The form is structured into multiple steps for enhanced user experience and organization of information.


# Main Form Components:

* UserForm: Captures user's first name, last name, and age.
* AddressForm: Captures user's street address, city, state, and zip code.
* AccountForm: Captures user's email address and password for account creation.
Each form component is encapsulated within a FormWrapper component, offering a title and structured layout for the form fields.


# State Management:
The form state is handled using React's useState hook, initializing the data with empty strings for each field.
The updateFields function is passed as a prop to each form component to manage the form state updates.

* Navigation:
Navigation between form steps is facilitated by a custom hook called useMultistepForm, managing the current step index and providing functions (back and next) for step navigation.

* Success Notification:
Upon successful completion of all form steps, a success message is displayed using the SweetAlert2 library. This offers a sleek and user-friendly confirmation to the user upon successful form submission.

# Overall:
This multi-step form application, constructed with TypeScript and incorporating SweetAlert2 for successful form submission notifications, delivers both a robust development experience and an intuitive user interface for creating accounts.