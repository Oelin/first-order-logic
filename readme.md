# First-order Logic

This library implements first-order logic in JavaScript, with an emphasis on semantic accuracy. It attempts to closely 
replicate the set-theoretic formalisation of first-order logic.


### Supported Concepts 

| Concept                                                                                          | Implementation                                                                                                                    |
|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| [First Order Language](https://en.wikipedia.org/wiki/First-order_logic#Syntax)                   | `FirstOrderLanguage(constantSymbols, variableSymbols, functionSymbols, predicateSymbols)`, `FirstOrderParser(firstOrderLanguage)` |
| [First Order Structure](https://en.wikipedia.org/wiki/First-order_logic#Semantics)               | `FirstOrderStructure(firstOrderLanguage, domain, constantsMap, functionsMap, predicatesMap)`                                      |
| [Interpreation Function](https://en.wikipedia.org/wiki/Interpretation_(logic))                   | `FirstOrderStructure.interpret(symbol)`                                                                                           |
| [Domain Of Discourse](https://en.wikipedia.org/wiki/Domain_of_discourse)                         | `FirstOrderStructure.domain`                                                                                                      |
| [Variable Binding](https://en.wikipedia.org/wiki/First-order_logic#Free_and_bound_variables)     | `FirstOrderAssignment(?variableMap)`                                                                                              |
| [Formula Evaluation](https://en.wikipedia.org/wiki/First-order_logic#Free_and_bound_variables)   | `FirstOrderEvaluator(firstOrderStructure, ?firstOrderAssignment)`                                                                 |


```js

```
