How I learn Scala 
==
As a beginner of Scala, I had been looking around for good resources which suit me to learn in a layer by layer way.   

### First step
I first watched the videos of the sytax, [Link](https://www.bilibili.com/video/av77135111/). This course contains 100
videos, each of them is around 5~8 mins. Most of the time I set the 2x speed when I watched them, but I usually stopped it and typed on my Scala 
repl to test the codes. [4 days] 

### Second Step 
After I watched all of the videos, I started to read the book [<\<Functional Programming in Scala>>](https://www.amazon.com/Functional-Programming-Scala-Paul-Chiusano/dp/1617290653), 
From this book, I learned what is functional programming, what is the benefits of using FP and the philosophy of FP. Those things are not 
covered by the videos but they are the most important parts. [1~2 weeks for 4 cheapters]

### Third Step
When I done reading the first 4 cheapters, I started to practice some (3~5) leetcode questions by using Scala. [3 days]  


### Fourth Step
I started to build a blog website using [scalatra](scalatra.org) as the web framework. I have compared some other web frameworks like Play which 
is the dominant one in Scala. However, I finnally chose to use Scalatra when I read the [philosophy of it](https://scalatra.org/guides/2.7/scalatra-philosophy.html). 
Scalatra is small and solid with high freedom for users. To build such a small project, I like it to be small and freedom! 

Followed by the document of scalatra, I used [SBT](https://www.scala-sbt.org/) which is based on Maven to build the project and control the dependecies. 
You can easily find everything on https://search.maven.org/ and put into the project.  

For database part, I used [c3p0](https://www.mchange.com/projects/c3p0/) to set up the connection to Mysql with pooling. 
I choose [Squeryl](https://www.squeryl.org/) which is an ORM language to talk with Mysql. This is something not handy and make me feel 
I don't like ORM at all. Even though Squeryl is more concise and easier to use than Hibernate etc. But, how can it be simpler than SQL? 
No matter the advantages of it like you don't need to change the codes when you change to use another SQL database like Oracle, I don't 
like ORM as it is fussy than SQL. 

To start the service, I used jetty. (I don't really care about it is using Tomcat or jetty or Jboss.)

