What is Closures?
1. Closure -> Its a type of function.
2. Function that "remembers" the variables from its lexical scope even after the outer function is completed its execution.
3. A Closure is created when a function is defined inside  another function and access variables from the outer function's scope.

function outerFunction(outerVariable) {
  return function innerFunction(innerVaraible) {
    console.log("Outer Variable:" + outerVariable);
    console.log("Inner Variable:" + innerVariable);
  };
}

const newFunction = outerFunction("outside");
newFunction("inside");

// Output:
Outer Variable: outside
Inner Variable: inner
