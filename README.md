# Compound Component Pattern
This small project was created as a practice for implementing Compound Component Pattern for a counter.

## What is Compound Component Pattern?
Compound Component Pattern allows us to create a set of related components that together achieve a common task. The examples of such tasks are modal windows, pagination, and tables.

One of the greatest advantages of using Compound Component Pattern is that we don't have to pass props around between the components, and we can avoid so called "prop explosion". Compound Component pattern uses context instead through which it provides access to state variables to all children components in a seamless and invisible way.

## How to establish a Compound Component pattern?
1. Create a context.
2. Create the parent component and wrap it with the context.
3. Create child components that will help implement the overall task of the compound component. They will have access to all state variables via the context.
4. (optional) Add child components as properties to the parent component.

