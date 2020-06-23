# Convert-orgon-trail-to-the-class-syntax

Recall how to convert prototype-style classes to the class-style syntax. Here's an example:

class Dog {
    constructor(name, breed, isGoodBoy) {
        this.name = name;
        this.breed = breed;
        this.isGoodBoy = isGoodBoy;
    }
    sit() {
        // sitting code here
    }
}
class GuardDog extends Dog {
    constructor(name, breed, isGoodBoy, attackWord) {
        super(name, breed, isGoodBoy)
        this.attackWord = attackWord
    }
    bark() {
        // barking code here
    }
}
Converted your program from the Extend Oregon Trail with Inheritance assessment over to the Class syntax.

Use the `class ClassName {}` statement for every class.

Use `constructor () {...}` to replace your constructor functions.

Use class methods to replace prototype methods.

Use `extends` and `super()` to implement inheritance in child classes.
