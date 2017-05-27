# ObjectDumper

This is a util class for print all properties of an object (when debugging).

## Usage

```
var obj = new SomeComplexClass
{
  Property1 = 123,
  Property2 = "Some Words"
}

var list = GetList<SomeComplexClass>();

ObjectDumper.Write(obj);  //print "Property1: 123 Property2: Some Words"
ObjectDumper.Write(list); //print all properties of each element in the list as one line
```
