# ExampleDeepClass class

A class with nested types.

```csharp
public class ExampleDeepClass
```

## Public Members

| name | description |
| --- | --- |
| [ExampleDeepClass](ExampleDeepClass/ExampleDeepClass.md)() | The default constructor. |
| class [NestedClass](ExampleDeepClass.NestedClass.md) | A nested class. |
| delegate [NestedDelegate](ExampleDeepClass.NestedDelegate.md) | A nested delegate. |

## Remarks

The [`ExampleDeepClass`](ExampleDeepClass.md) class has a [`NestedDelegate`](ExampleDeepClass.NestedDelegate.md) and a [`NestedClass`](ExampleDeepClass.NestedClass.md)with a [`VeryNestedStruct`](ExampleDeepClass.NestedClass.VeryNestedStruct.md) and a [`VeryVeryNestedInterface`](ExampleDeepClass.NestedClass.VeryNestedStruct.VeryVeryNestedInterface.md). Another type in this namespace is [`ExampleClass`](ExampleClass.md) with method [`Create`](ExampleClass/Create.md). A type in an inner namespace is [`ExampleInnerClass`](../ExampleAssembly.InnerNamespace/ExampleInnerClass.md), which has a constructor [`ExampleInnerClass`](../ExampleAssembly.InnerNamespace/ExampleInnerClass/ExampleInnerClass.md).

## See Also

* namespace [ExampleAssembly](../ExampleAssembly.md)
* [ExampleDeepClass.cs](../../tests/ExampleAssembly/ExampleDeepClass.cs)

<!-- DO NOT EDIT: generated by xmldocmd for ExampleAssembly.dll -->