<snippet>
#Direct Method Invocation
Direct Method Invocation is a communication pattern in iOS where one sender talks to one receiver with tight coupling. This is an implementation of the Direct Invocation Method in Swift Playgrounds.

##How it Works
1. A class called Person has a property of name of type String and accepts 2 kinds of messages:
  * A message that will make the Person print its name, for example: "My name is John"
  * A message in which the sender can attach another Person as payload and the receiving object will greet that Person by printing a message, for example: "Hello, John"
</snippet>
