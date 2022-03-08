# React Testing


## react-testing-library

React DOM testing utilities

- [Docs](https://testing-library.com/docs/react-testing-library/intro/)

```
npm install --save-dev @testing-library/react @testing-library/jest-dom @testing-library/user-event@^14.0.0-beta msw
```

### Key concepts

- [Query methods](https://testing-library.com/docs/queries/about#types-of-queries): getBy, queryBy, findBy (waits for content)
- [Query method priority](https://testing-library.com/docs/queries/about#priority): byRole, byLabelText, byText, byTestId
- [User events](https://testing-library.com/docs/user-event/intro): click events, user typing
- [Assert using w/ jest-dom matchers](https://testing-library.com/docs/ecosystem-jest-dom)
- [react-router MemoryRouter](https://reactrouter.com/docs/en/v6/api#memoryrouter)

### Examples

- [Docs example](https://testing-library.com/docs/react-testing-library/example-intro/#full-example)
- [stock-app example](https://github.com/bryanyee/stock-app/blob/main/src/components/App.test.js)


## mock-service-worker

API mocking library

- [Docs](https://mswjs.io/docs/getting-started/mocks/rest-api)

### Examples
- [Docs example](https://mswjs.io/docs/api/setup-server)
- [react-testing-library example](https://testing-library.com/docs/react-testing-library/example-intro#mock)
- stock-app example:
  - [Test setup](https://github.com/bryanyee/stock-app/blob/main/src/setupTests.js)
  - [Define handlers](https://github.com/bryanyee/stock-app/blob/main/src/mockHandlers.js)
