# Design Pattern

**Our cookbook**

1. Context API
2. Presentation/Conrainer Components
3. Render Props

# React-Design-Pattern-Container_View-

check it out `https://www.uxpin.com/studio/blog/react-design-patterns/`

Container-View pattern is the most efficient and widely used feature building pattern in react environment.

**Container Component**
Responsibilities of a container component are:

```
1. data fetching
2. redux integration
3. side-effects handling, heavy computation or data mapping
4. finally pass the required props down to the view
```

**View Component**
should contain only the presentation part

```
1. All the UI/presentation logic will reside here
2. Further complex elements can be broken down into individual components for ease of maintenance.
3. Presentational components utilize props, render, and context.
4. Presentational components receive data and callbacks from props only, which can be provided by its container or parent component
```

**PropTypes**
 It is a very good practice to declare propTypes for all the components that are expecting props from their parents. This enables type-checking, properties availability, and jots down all the required properties with their data-types at one place.
