#### Questions

> Read React's documentation on [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html).

A:

> Read [Why does React emphasize on unidirectional data flow and Flux architecture?](https://hashnode.com/post/why-does-react-emphasize-on-unidirectional-data-flow-and-flux-architecture-ciibz8ej600n2j3xtxgc0n1f0) on Hashnode.

A:

> Why does React only allow information to be passed down in the hierarchy? What are the advantages and disadvantages of this approach? Discuss this topic with your mentor.

A: React only allows information to be passed down in the hierarchy because you can place the single component that mutates state on top, everything below changes deterministically, and therefore your app behaves predictably.  This makes components less coupled and therefore easier to debug.  You can also control information flow easily if it only goes in one direction.  The main drawback of one way (unidirectional) data binding is that you need to write more boiler-plate code.
