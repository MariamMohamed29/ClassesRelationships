# ClassesRelationships
## In object-oriented programming, there are several types of relationships that can exist between classes. Here are some of the commonly encountered types:
### 1-Association:
Association represents a relationship between two classes where objects of one class are connected to objects of another class. It can be a one-to-one, one-to-many, or many-to-many relationship. **For example**, a Car class may be associated with a Driver class, where each car has a driver.
### 2-Aggregation:
Aggregation is a specialized form of association where one class represents a whole and another class represents a part. The part can exist independently of the whole. It is denoted by a diamond-shaped arrow.**For example**, a Organization class may have an aggregation relationship with a Person class, where a Person is a part of the Organization.
### 3-Composition:
Composition is a stronger form of aggregation where the part cannot exist without the whole. The lifetime of the part is controlled by the whole. It is denoted by a filled diamond-shaped arrow.**For example**, a Car class may have a composition relationship with a Engine class, where a Engine cannot exist without the Car.
### 4-Inheritance:
Inheritance represents an "is-a" relationship between classes, where one class (subclass) inherits the properties and behaviors of another class (superclass). The subclass extends or specializes the superclass.**For example**, a Vehicle class can inherit from an Car class, as a Car is a type of Vehicle.
### 5-Realization/Implementation:
Realization or implementation represents the relationship between an interface (or abstract class) and the class that implements it. The implementing class provides the implementation for the methods defined in the interface.**For example**, a Circle class may realize an Shape interface, implementing the calculateArea() method.
