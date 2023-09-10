# Testing Input Output

[Angular Challenges](https://github.com/tomalaforge/angular-challenges) #19 Input / Output Testing

## Built With

- [Angular](https://angular.io)
- [Angular CLI](https://github.com/angular/angular-cli) version 16.2.0.
- [Testing Library Angular](https://testing-library.com/docs/angular-testing-library/intro)
- [Jest](https://jestjs.io)
- [Cypress](https://www.cypress.io)

## Directions

We have a small counter application that increment or decrement a number.

The goal is to test CounterComponent with Testing library and Cypress.

## Thoughts

- I tried to use componentProperties for the output test but I don't think it is possible.
- You get errors `Property 'toHaveTextContent' does not exist on type 'Assertion'` etc after you write cypress tests.  
- Both tests still work -> seems like vscode gets confused ? 

## How to Use

```bash 

git clone https://github.com/jdegand/testing-input-output.git

# cd into the directory
npm install

# Jest 

npm test

# Jest with Coverage

npm run test:coverage

# Cypress

npm run cypress:open
```

## Useful Resources

- [Angular Testing Library](https://testing-library.com/docs/angular-testing-library/examples) - angular testing library counter example
- [YouTube](https://www.youtube.com/watch?v=c57llB8QA2E) - I bet you can write an Angular UNIT TEST after this video
- [Stack Overflow](https://stackoverflow.com/questions/58976251/checking-text-appears-inside-an-element-using-react-testing-library) - checking text appears inside an element using react testing library
- [Stack Overflow](https://stackoverflow.com/questions/49096093/how-do-i-test-a-jest-console-log) - how do i test a jest console.log
- [Stack Overflow](https://stackoverflow.com/questions/46817783/angular-unit-test-that-a-components-output-is-not-emitted) - angular unit test that a component's output is not emitted
- [Stack Overflow](https://stackoverflow.com/questions/53775176/how-to-unit-test-an-angular-output) - how to unit test an angular output
- [Stack Overflow](https://stackoverflow.com/questions/42302114/testing-that-a-component-method-calls-another-method) - testing that a component method calls another method
- [Github](https://github.com/testing-library/angular-testing-library/blob/main/apps/example-app/src/app/examples/02-input-output.spec.ts) - input output spec example from angular testing library
- [Blog](https://chrisboakes.com/mocking-javascript-class-inner-functions-with-jest/) - mocking javascript class inner functions with jest
- [Cypress Docs](https://docs.cypress.io/guides/component-testing/angular/api) - angular api
- [Cypress Docs](https://docs.cypress.io/guides/component-testing/angular/examples) - angular examples