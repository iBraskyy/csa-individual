{% include navigation.html %}

## Techtalks (notes)

All my notes for CSA tech talks

### Techtalk 0

#### Programming Paradigms:

**Imperative Paradigm:**

Data Structures is a method of storing data for code: class, list, CRUD database, etc. 
- can implement o notation into data structure

**Object Oriented Paradigm:**

**Arrays and lists**

```java
public static Animal[] animalData() {
	return new Animal[]{
	        new Animal("Lion", 8, "Gold"),
	        new Animal("Pig", 3, "Pink"),
		new Animal("Robin", 7, "Red"),
		new Animal("Cat", 10, "Black"),
		new Animal("Kitty", 1, "Calico"),
		new Animal("Dog", 14, "Brown")
	};
}
```

**Hash maps**

```java
private final Map<String, Integer> OPERATORS = new HashMap<>();
{
  OPERATORS.put("*", 3);
  OPERATORS.put("/", 3);
  OPERATORS.put("%", 3);
  OPERATORS.put("+", 4);
  OPERATORS.put("-", 4);
}
```
