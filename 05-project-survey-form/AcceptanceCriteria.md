# Acceptance Criteria: freeCodeCamp (New) Responsive Web Design Survey Form Project

https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-survey-form-project/build-a-survey-form

---

## Objective
Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

## Acceptance Criteria
- [X] You should have a page title in an `h1` element with an `id` of `title`
- [X] You should have a short explanation in a `p` element with an `id` of `description`
- [X] You should have a `form` element with an `id` of `survey-form`
- [X] Inside the form element, you are required to enter your name in an `input` field that has an `id` of `name` and a `type` of `text`
- [X] Inside the `form` element, you are required to enter your email in an `input` field that has an `id` of `email`
- [X] If you enter an email that is not formatted correctly, you will see an HTML5 validation error
- [X] Inside the form, you can enter a number in an `input` field that has an `id` of `number`
- [X] If you enter non-numbers in the number input, you will see an HTML5 validation error
- [X] If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error
- [X] For the name, email, and number input fields, you can see corresponding `label` elements in the form, that describe the purpose of each field with the following ids: `id="name-label"`,` id="email-label"`, and `id="number-label"`
- [X] For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
- [X] Inside the form element, you should have a `select` dropdown element with an `id` of `dropdown` and at least two options to choose from
- [X] Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the `name` attribute
- [X] Inside the form element, you can select several fields from a series of checkboxes, each of which must have a `value` attribute
- [X] Inside the form element, you are presented with a `textarea` for additional comments
- [X] Inside the form element, you are presented with a button with `id` of `submit` to submit all the inputs

## Tests
- You should have an `h1` element with an `id` of `title`.
- Your `#title` should not be empty.
- You should have a `p` element with an `id` of `description`.
- Your `#description` should not be empty.
- You should have a `form` element with an `id` of `survey-form`.
- You should have an `input` element with an `id` of `name`.
- Your `#name` should have a `type` of `text`.
- Your `#name` should require `input`.
- Your `#name` should be a descendant of `#survey-form`.
- You should have an `input` element with an `id` of `email`.
- Your `#email` should have a `type` of `email`.
- Your `#email` should require input.
- Your `#email` should be a descendant of `#survey-form`
- You should have an `input` element with an `id` of `number`.
- Your `#number` should be a descendant of `#survey-form`.
- Your `#number` should have a `type` of `number`.
- Your `#number` should have a `min` attribute with a numeric value.
- Your `#number` should have a `max` attribute with a numeric value.
- You should have a `label` element with an `id` of `name-label`.
- You should have a `label` element with an `id` of `email-label`.
- You should have a `label` element with an `id` of `number-label`.
- Your `#name-label` should contain text that describes the input.
- Your `#email-label` should contain text that describes the input.
- Your `#number-label` should contain text that describes the input.
- Your `#name-label` should be a descendant of `#survey-form`.
- Your `#email-label` should be a descendant of `#survey-form`.
- Your `#number-label` should be a descendant of `#survey-form`.
- Your `#name` should have a `placeholder` attribute and value.
- Your `#email` should have a `placeholder` attribute and value.
- Your `#number` should have a `placeholder` attribute and value.
- You should have a `select` field with an `id` of `dropdown`.
- Your `#dropdown` should have at least two selectable (not disabled) `option` elements.
- Your `#dropdown` should be a descendant of `#survey-form`.
- You should have at least two `input` elements with a `type` of `radio` (radio buttons).
- You should have at least two radio buttons that are descendants of `#survey-form`.
- All your radio buttons should have a `value` attribute and value.
- All your radio buttons should have a `name` attribute and value.
- Every radio button group should have at least 2 radio buttons.
- You should have at least two `input` elements with a `type` of `checkbox` (checkboxes) that are descendants of `#survey-form`.
- All your checkboxes inside `#survey-form` should have a `value` attribute and value.
- You should have at least one `textarea` element that is a descendant of `#survey-form`.
- You should have an `input` or `button` element with an `id` of `submit`.
- Your `#submit` should have a `type` of `submit`.
- Your `#submit` should be a descendant of `#survey-form`.
