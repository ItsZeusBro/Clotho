# Clotho
## Clotho plugs into Moira. Clotho Spins Uncaught Exceptions back into a Predefined State for your Moira Machine
![images](https://user-images.githubusercontent.com/107733608/174721787-4ca29740-197e-4491-bd3b-d640cb2bd5ad.jpg "It is said that Clotho brought Pelops back to life, with the exception of a shoulder which was eaten by Demeter, which was replaced by a chunk of ivory")


### Clotho "Spins the Thread" of your app's exception handling. 

It uses Moira (State Machine Framework) to create a transition state for any uncaught exceptions in the input for any particular Moira state. Basically it's an exception handler for a state machine called Moira.

Clotho wraps Herself around Moira and catches uncaught behavior and redirects it to some general state as well 

Clotho asks: "What is tragedy, without good fate and ability to recover?" In otherwords, what is the purpose of Tradgedy without Moira and Clotho?

Clotho watches your application and reports general uncaught exceptions so that you know when users are running into undefined abstract states, even though Clotho sends them to a concrete predefined general state, or specific state (depending on your choice)

Clotho allows you to have a spectrum of generality over exception handling and the states it routes them to in Moira. For example, you can create a subset of states that route to a general state when experiencing uncaught exceptions. Or you can give them all their own meta-context exception handle to present another layer of logic that kicks in depending on the underlying context for robust exception handling with general context based rules using the stacktrace.

Clotho sends feedback to your CI/CD pipeline
