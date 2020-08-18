# androidReadWriteTo
## Idea
This GitHub project can help you this android development if you want to have a fast methods for saving and reading data from txt files in external storage.
## Methods
Method to write data to file:
```kotlin
fun writeToSDFile(filename: String, inf: String)
```
It takes 2 attributes:
1. filename type string
2. data type string

First attribute is only the name of the file so you don't have to write absolute path of the file.

Second attribute is a value that you want to save.

If file does not exists this functions returns error stack trace.
Method for read data from file:
```kotlin
fun getValues(filename: String, basicMeaning: String):String
```
It takes 2 attributes:
1. filename type string
2. default meaning of your data type string

First attribute is also only the name of the file.

Second attribute is deafult value of the data you wants to save.

If file does not exists it's creating this file with basic meaning.

Method to delete file:
```kotlin
fun deleteFile(filename: String): Boolean
```

It takes only one attribute: filename type string and returns true if deleated and false if not.
