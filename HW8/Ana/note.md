1. What is Jest?
Jest is a JavaScript testing framework commonly used for testing React applications. It provides a test runner, assertion library, mocking utilities, and snapshot testing out of the box.

2. What is a test case in Jest?
A test case is a block of code that verifies a specific behavior of a function or component. In Jest, test cases are written using test() or it().

3. What does expect do in Jest?
expect creates an assertion that checks whether a value meets certain conditions. It is used together with matchers like toBe or toEqual to validate test results.

4. What is the difference between .toBe() and .toEqual()?
.toBe() checks for strict equality using Object.is, making it suitable for primitive values. .toEqual() performs a deep comparison, which is ideal for objects and arrays.

5. How do you test if a React component renders correctly?
You can render the component using React Testing Library and assert that expected elements appear in the document. This verifies that the component renders without errors and displays correct content.

6. How do you simulate a button click in a test?
You can simulate a button click using fireEvent.click() or userEvent.click() from React Testing Library. This allows you to test user interactions and resulting behavior.

7. How do you mock a function with Jest?
You can mock a function using jest.fn() or mock an existing module with jest.mock(). Mock functions let you track calls, arguments, and return values.

8. What is snapshot testing and how do you utilize it?
Snapshot testing captures a rendered component’s output and saves it as a snapshot file. Future test runs compare against the snapshot to detect unexpected UI changes.
