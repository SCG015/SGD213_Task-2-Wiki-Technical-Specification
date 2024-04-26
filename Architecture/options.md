# TOP HEADING

You should consider 3 different architecture options in here.

You **don't** need UML in here.

You should also justify your thinking.

Hot tip: use our text book for guidance.

## Option 1
We have a Characterbase
Our CharacterBase has a component that uses IMovable
Our PlayerCharacter inherits from CharacterBase
Our PlayerController interacts with IMovable
Our EnemySentry inherits from CharacterBase
Our AIController interacts with IMovable
Our EnemyCamera has a component called ViewCone


Using both inheritance and interfaces





## Option 2
Our PlayerCharacter has a component that uses IMovable
Our PlayerController interacts with IMovable
Our EnemySentry has a component that uses IMovable
Our AIController interacts with IMovable
Our EnemyCamera has a component called ViewCone

Using interface


## Option 3
We have our PlayerCharacter game object
It has a rigidbody component
playercontroller directly touches the Rigidbody component, instead of going via an engine component

Using just components
