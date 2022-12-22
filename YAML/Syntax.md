### Key Value pair

```yaml
Name: "Shivang Shandilya"
1: "This a list"
```

### List

```yaml
- guava
- mango
- cherry
- banana
```
or

```yaml
cities: [new delhi, torronto, new york, mumbai]
```

### String and Variables

```yaml
name: Shivang Shandilya
fruit: "Mango"
job: 'Student'
age: 19
marks: 10.33
booleanValue: No, N, fasle, Fasle, FALSE 
```

### Multiline String

```yaml
Address: |
  01
  Delhi
  India
```
Single line in multiple line.

```yaml
message: >
  This all
  will be in a single
  line

```

### Nested Mapping

```yaml
names: Shivang
role:
  age: 19
  job: student
```  

### Nested Sequence

```yaml
-
  - mango
  - apple
  - banana
-
  - marks
  - roll
```

##### Specify the data type

```yaml

# Integer
Zero: !!int 0
postiveNumber: !!int 45
negativeNumber: !!int -45
hexa: !!int 0x45

# Float
mark: !!float 56.55
infinity: !!float .inf
not a num: .nan
itNot: !!bool false

# String
string: !!str "hello"

# Null
surnmae: !!null #null or NULL ~ 
~: this a null key

# Exponential Numbers
myNum: 6.22ES56

# Dates and time
date: !!timestamp 2002-01-02
no Time zone: 2012-12-15T02:59:43
India Time: 2012-12-15T02:59:43 +5:30
```
