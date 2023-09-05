
# Learning-React

This dedicated space has been established to house a myriad of projects centered on React, one of the most innovative and widely-used JavaScript libraries in the world. 

# Important react concepts

## Components

There is functional components and class components. Interface part.

## Functional Components

Javascript/ES6 function that returns an React(JSX) element.

```react
Example:

function Salute(props) {
    return <h1>Hi, props.name </h1>;
}

```

### Caracteristics

1. It returns an React element.
2. It must to start with an upper letter the name of the function.
3. It can receive values.

### Props

- Argument that a React component can receive.
- Only can be used from father to child.

## Class Component

Javascript/ES6 function that returns an React(JSX) element.


```react
class Salute extends React.Component{
    render(){
       return <h1>Hi, this.props.name </h1>;
    }
}
```

### Caracteristicas

1. It must to extends `React.Component`
2. It must have a `render` method to return a jsx element.
3. It can receive values.
4. When we use the props we must to use this.

## State

The representation in javascript of the property of one component and his currents values.

## Hooks

It let us add properties to owr components. It let you work with the functional components states.

## Event Listener

Javascript function that is executed when a specific event occurs.
