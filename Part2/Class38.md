# Lab 38

## Readings: React 2

## [Link](./Class38.md)

#### How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?

    - In a React application, components are often organized in a hierarchical structure, with child components nested within parent components. 

    -  When a piece of state is required by multiple components, rather than duplicating that state in each of those components, you can lift the state up to a common parent component

    - the parent component becomes the source of truth for that piece of state, and it passes down the necessary data to its child components via props.

#### Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.

    - Conditional rendering in React refers to the practice of showing or hiding certain parts of a component's UI based on a condition or set of conditions. It allows you to dynamically decide what content should be rendered based on the current state or props of the component. 

    - This is a powerful technique that enables you to create more flexible and responsive user interfaces.

    Ex:

    class ConditionalRenderingExample extends         
    
    Component {
    constructor(props) {
        super(props);
        this.state = {
        isLoggedIn: false,
        };
            }


#### What are the main principles behind “Thinking in React” and how do they guide the process of designing and building a React application?

    - Component-Oriented Thinking

    - Single Responsibility Principle

    - Data Flow and State Management

    - Unidirectional Data Flow

    - Reusability and Composition

    - Separation of Concerns

    - UI as a Function of State

#### Things I want to know more about

        - know more about Nextjs 