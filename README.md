# DbmlToClass
Allows you to easily generate portable C# classes from a LINQ-to-SQL DBML file

This is a simple utility that takes your DBML files and turns them into stand-alone classes.

Usually, in a project you can reference the LINQ-to-SQL classes and there is no need to generate your own.

But if you have a Xamarin app for example, communicating over generic handlers, then it could become necessary to pass whole business objects back and forth.

By using DbmlToClass, you can satisfy the requirement even though the phone application has no knowledge of the database.
