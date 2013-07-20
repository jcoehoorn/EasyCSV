EasyCSV v0.1
=======

Fast, zero-config CSV reader in one source file that can be included in a .Net Project

Based on my CSV Reader initially posted to this Stack Overflow question:  
http://stackoverflow.com/a/1544743/3043
What sets this CSV reader apart:

1. You can point it at any csv stream without knowing what kind of records the stream contains, and it will return nice data
2. It



Just include EasyCSV.cs in your CSharp Project

Roadmap to 1.0:

.1 Initial upload  
.2 Add Visual Studio solution with Unit Tests  
.3 Convert to inherit from TextReader  
.4 Add options: delimiter, error handling, escaping  
.5 Add support for projecting records to a POCO instead of a List<string>  
.6 Initial write support  
.7 Refine write support

1.1 VB.Net Translation
