EasyCSV v0.1
=======

Fast, zero-config CSV reader in one source file that can be included in a C# Project

Based on my CSV Reader initially posted to this Stack Overflow question:  
http://stackoverflow.com/a/1544743/3043

####What sets this CSV reader apart:

1. Point it at any csv stream without knowing what kind of records the stream contains, and it will return nice data.  
Most current readers want you to tell your object up front what you expect in the CSV data, and will throw errors if the content is different.  
2. Lazy reads. Need just the first few records? Read just the first few records. Don't know? Read until you find what you're looking for.
3. Works well with linq-to-objects
4. Should perform *very* well, though I have not yet thoroughly benchmarked it

Just include EasyCSV.cs in your CSharp Project, and let Intellisense tell you how to use it.

####Roadmap Milestones for 1.0:

.1 Initial upload  
.2 Add Visual Studio solution with Unit Tests  
.3 Convert to inherit from TextReader  
.4 Add better support for header rows  
.5 Add support for projecting records to a POCO instead of a List<string> (can do this now, but it would waste work done creating the list)  
.6 Add options: delimiter, error handling, escaping, more  
.7 Initial write support   
.8 Documentation   
.9 Performance optimizations  
1.0 Bug squash  

1.1 VB.Net Translation  
1.2 F# Translation
