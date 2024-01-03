# React Cheat Sheet

A cheat sheet for React developers, providing a quick reference guide for common React concepts, syntax, and APIs.

## Table of Contents

- [Components](#components)
- [Props](#props)
- [State](#state)
- [Lifecycle Methods](#lifecycle-methods)
- [Hooks](#hooks)
- [Event Handling](#event-handling)
- [Conditional Rendering](#conditional-rendering)
- [List Rendering](#list-rendering)
- [Forms](#forms)
- [Styling](#styling)
- [Routing](#routing)
- [Context API](#context-api)
- [Error Boundaries](#error-boundaries)
- [Testing](#testing)

## Components

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| class MyComponent extends React.Component { } | Class component declaration                     |
| function MyComponent() { }         | Functional component declaration                 |
| render() { }                       | Component's render method                        |
| this.props                         | Accessing props inside a component               |

## Props

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| props                              | Data passed to a component from its parent        |
| this.props.propName                | Accessing a specific prop value                   |
| defaultProps                       | Setting default props for a component             |

## State

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| state = { }                        | Initializing component state                      |
| this.state                         | Accessing the current state                       |
| this.setState({ })                 | Updating the component's state                    |
| useState(initialValue)             | Using the state hook in functional components     |

## Lifecycle Methods

| Method                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| componentDidMount()                | Executed after the component is mounted           |
| componentDidUpdate(prevProps, prevState) | Executed after a component is updated         |
| componentWillUnmount()             | Executed before the component is unmounted        |

## Hooks

| Hook                                 | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| useState(initialValue)             | Managing state in functional components           |
| useEffect(callback, dependencies)  | Executing side effects in functional components   |
| useContext(context)                | Accessing the value of a context                  |

## Event Handling

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| onClick={handler}                  | Handling click events                             |
| onChange={handler}                 | Handling input change events                      |
| onSubmit={handler}                 | Handling form submission                          |

## Conditional Rendering

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| if (condition) { }                 | Conditional rendering with if statements        |
| { condition && <Component /> }     | Conditional rendering with logical && operator  |
| { condition ? <Component /> : null } | Conditional rendering with ternary operator     |

## List Rendering

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| array.map(item => { })             | Rendering a list of items                         |
| key={item.id}                      | Providing a unique key for list items             |

## Forms

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| onChange={handler}                 | Handling form input change                        |
| onSubmit={handler}                 | Handling form submission                          |
| event.preventDefault()             | Preventing the default form submission behavior    |

## Styling

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| Inline Styles                        | Adding inline styles to a component               |
| CSS Modules                          | Using CSS modules for component styling           |
| Styled Components                    | Creating styled components with CSS-in-JS         |

## Routing

| Library/Framework                    | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| react-router-dom                   | Declarative routing for React applications        |

## Context API

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| React.createContext()               | Creating a new context                            |
| Context.Provider                   | Providing a value to the context                  |
| Context.Consumer                   | Accessing the value from the context              |

## Error Boundaries

| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| componentDidCatch(error, info)      | Handling errors within a component                |
| static getDerivedStateFromError(error) | Updating state based on error                     |

## Testing

| Library/Framework                    | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| react-testing-library              | Testing React components                          |
| jest``markdown
| Syntax                               | Description                                      |
| ------------------------------------ | ------------------------------------------------ |
| jest.mock('moduleName')            | Mocking a module for testing                      |
| render(<Component />)              | Rendering a component for testing                 |
| fireEvent.event(element, data)      | Triggering an event on a component                |
| expect(element).toHaveTextContent(text) | Asserting text content of an element            |
