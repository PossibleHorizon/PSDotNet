# PSDotNet
Practical Example of Using Photoshop DotNet Wrapper Class


<B>PsDotNet Diagram</B>
<br>
Many of the collections implement a ILookup interface with the key being the name of the element and the value will be IEnumerable of the type of element. This was the best solution to account duplicates. To help visualize the dependencies please refer to the following dependency diagram,
</br>

<img src="https://thepossiblehorizon.files.wordpress.com/2016/11/psdotnetdiagram2.png">
<br>
While PsDotNet surfaces everything that the COM library exposes, there may be functionality that is missing. Additionally, there may be a need to automate 3rd party plug-ins. PsDotNet Listener is a standalone WPF application that is intended to help developers extend what PsDotNet can do. It provides the developer the ability to echo back simplified Javascript and C# code snippets as actions are performed in Photoshop. These snippets can then be copied and pasted directly into a C# project using PsDotNet and used and modified as necessary. It’s so much better and intuitive than the build-in Photoshop plug-in Listener.8li.
</br>

<br><B>PsDotNet Listener</B></br>
<br>
It’s simple, neat and straight forward to get tasks done efficiently in Photoshop from third-party host applications. For game editor such as Unity with C# and Javascript supported as native scripting languages, all kinds of Photoshop tasks can be carried on right within Unity with PsDotNet library. There are a lot of potentials what can be done with it.
</br>
