# Business Analytics Student Survey - Liao Zhu

## Description
This project is a multi-page web form designed to collect survey data from Business Analytics students. It is built using HTML5, CSS3, Bootstrap 5.3, and Font Awesome, and is deployed as a static site using Azure for easy access and testing.

## Best Practices for Forms
This web form follows best practices in form design by ensuring that each input field is clearly labeled, includes appropriate placeholders, and uses built-in HTML5 validations (e.g., the `required` attribute) to prevent incomplete submissions. The layout is responsive since we used bootstrap. Furthermore, the form is organized into logical sections with clear progress indicators (e.g., "Page 1 of 2") that guide the user through the process.

To enhance user experience, the form uses features such as autofocus on the first input field and custom tooltips for context-sensitive help. For example, the tooltip on the "My home town is" field provides users with extra information about the data being requested, all while maintaining a clean interface. The use of dropdown menus for selection fields minimizes errors and simplifies input, ensuring that the data collected is both accurate and consistent.

The implementation of best practices is evident in the careful consideration of form validation and feedback. When a user submits the form, JavaScript validation is triggered to ensure that all required fields are filled, providing immediate visual feedback if corrections are needed. This approach not only improves data quality but also enhances the overall user experience by making the form intuitive and easy to navigate.

## Accessibility Considerations
The web form uses semantic HTML elements (such as `<form>`, `<label>`, and `<input>`) to facilitate navigation by screen readers. All interactive elements are properly labeled to ensure that users with visual impairments can understand the purpose of each field. The design also incorporates sufficient color contrast and legible font sizes, making the form usable for a wide range of users. Lastly, items such as image alt texts are utilized for any people using screen readers.