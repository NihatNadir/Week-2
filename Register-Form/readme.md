# Survey Form Project

This project is a **Survey Form** built to practice **HTML** and **CSS** skills, following specific requirements for a structured and user-friendly form design. Below are the implemented features:

---

## 1. **Page Title**
- The page contains a title within an `<h1>` element.
- The `id` of the `<h1>` element is `title`.

---

## 2. **Description**
- A short description of the form is provided inside a `<p>` element.
- The `id` of the `<p>` element is `description`.

---

## 3. **Form Element**
- The form is contained within a `<form>` element.
- The `id` of the `<form>` element is `survey-form`.

---

## 4. **Name Input Field**
- A text input field for entering the user's name.
- The input element:
  - Has the `id` attribute set to `name`.
  - Has the `type` attribute set to `text`.
- The input field includes a placeholder for user guidance.

---

## 5. **Email Input Field**
- An email input field for entering the user's email address.
- The input element:
  - Has the `id` attribute set to `email`.
  - Has the `type` attribute set to `email`.
- Invalid email formats trigger HTML5 validation errors.

---

## 6. **Number Input Field**
- A number input field for entering a numeric value.
- The input element:
  - Has the `id` attribute set to `number`.
  - Has the `type` attribute set to `number`.
- The input field:
  - Accepts only numeric values.
  - Enforces a minimum and maximum range.
- Invalid input triggers HTML5 validation errors.

---

## 7. **Labels**
- The form includes labels for the name, email, and number input fields.
- Labels have the following `id` attributes:
  - `name-label` for the name field.
  - `email-label` for the email field.
  - `number-label` for the number field.
- Placeholder text provides additional guidance for these fields.

---

## 8. **Dropdown**
- A dropdown `<select>` element allows users to select an option.
- The dropdown:
  - Has the `id` attribute set to `dropdown`.
  - Includes at least two selectable options.

---

## 9. **Radio Buttons**
- At least two radio buttons are included in the form, grouped using the `name` attribute.
- Each radio button allows the user to select an option, such as a source where they heard about the service.

---

## 10. **Checkboxes**
- The form includes at least two checkboxes.
- Each checkbox:
  - Has a `value` attribute.
  - Represents options like agreeing to terms of service or subscribing to a newsletter.

---

## 11. **Text Area**
- A `<textarea>` element is included for the user to add additional comments or suggestions.

---

## 12. **Submit Button**
- The form contains a submit button to send the data.
- The button:
  - Is implemented as an `<input>` element.
  - Has the `id` attribute set to `submit`.

---

## Technologies Used
- **HTML5**: To structure the form elements and enforce validation.
- **CSS3**: For styling the form layout, inputs, and buttons.