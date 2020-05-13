# Memento Pattern
Memento is another Behavioral Pattern. This pattern can be used to create snapshots of an object so that we can revert to it. Object whose state we want to save, creates a snapshot or memento of itself and passes it's reference to Caretaker object. This caretaker object saves this memento in a container. These states in Caretaker object are kept until object wants revert itself to that state. 

To boil it down, "**The main purpose of the Memento pattern is to save the internal state of an object and the possibility of restoring it again if necessary, without disturbing encapsulation**."
