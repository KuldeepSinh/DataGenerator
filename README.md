# DataGenerator
A rule based data generator to generate high-quality random data for interrelated Data Objects! 

### What is it?
Let's disect above description...
1. A rule based data generator : Users define rules to control the value to be randomized. For example, user can define a rule to generate customer's age to be between 5 to 100 years. Such an ability to control values in a declarative way allows the generator to generate high-quality random data.
2. Interrelated Data Objects : Generally, Data Objects, also known as Entities, we want to generate are interrelated. For example a custromer can have many purchases. The generator, walks down to the entier object graph and generates data. The users are requierd to provide rules for each of the entities they want to generate data for. 

### Why?
If you are like me, you may already know the real pain of validating/testing data intensive applications is not having easy way access real/realistic data. Or even its prohibited to access real data behind some statutary or international data privacy laws, like, HIPAA, GDPR, etc. This utility is aimed to generate high quality random data. Whether you want data for a single entity or a graph of interrelated entities, this utility generates data, defined by your rules.

### How?
1. Define your interrelated data objects as Java Beans/Entities. Java Beans are bare minimum classes difined to represnt entities. They have a set of fields, constructors and getters and setters for each of the fields.
2. Define set of rules to control value of each field of the Java Bean. The rules are defined in a JSON file for ease and familiarity.
3. Run the generator!

### Example
<comming soon>
