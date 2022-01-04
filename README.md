# Java8InAction
Java8 Programming Concepts

**Chapter 1**
* Method References - [Method Reference Example - FilteringApples](https://github.com/ishan-aggarwal/Java8InAction/blob/main/lambdasinaction/chap1/FilteringApples.java)

**Chapter 2**
* Passing code with behavior parameterization - [Custom Predicate Example - FilteringApples](https://github.com/ishan-aggarwal/Java8InAction/blob/main/lambdasinaction/chap2/FilteringApples.java)

* Behavior parameterization vs. value parameterization
![image](https://user-images.githubusercontent.com/12678869/148015455-3e06344b-edec-4c8f-8b27-3d6aaf67f2f0.png)

* Abstracting over List type

![image](https://user-images.githubusercontent.com/12678869/148015681-40044d6f-2cb2-4f19-a98b-e21ca681b194.png)

* **Summary**

 Behavior parameterization is the ability for a method to take multiple different behaviors as parameters and use them internally to accomplish different behaviors.

 Behavior parameterization lets you make your code more adaptive to changing requirements and saves on engineering efforts in the future.

 Passing code is a way to give new behaviors as arguments to a method. But it’s verbose prior to Java 8. Anonymous classes helped a bit before Java 8 to get rid of the verbosity associated with declaring multiple concrete classes for an interface that are needed only once.

 The Java API contains many methods that can be parameterized with different behaviors, which include sorting, threads, and GUI handling.

