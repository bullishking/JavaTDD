## JavaTDD
<p align="center">
  <a href="https://github.com/fengyuanyang/JavaTDD/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/fengyuanyang/JavaTDD?color=0088ff" />
  </a>
  <a href="https://github.com/fengyuanyang/JavaTDD/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/fengyuanyang/JavaTDD?color=0088ff" />
  </a>
</p>

## Table of contents
### Java fundamentals
1. String - "Hello, world".
2. Conditions - > , < , >=, <=, ==, != 
3. Statements - if/else, switch.
4. Primitive - byte, short, int, long, float, double, boolean, char and test their edges.
5. Loops - while loop and for loop.
6. Exception - TBD.    
7. Design Pattern - TBD.        

more...
### Code expected
* Proper naming for variables, avoid using i,v,k...etc. The variable name should be self explanatory.
* Proper names for files.
* Follow unit tests naming conventions - **MethodName_StateUnderTest_ExpectedBehavior**.

```
    String hello(String name) {
        return "Hello World " + name;
    }

    @Test
    void hello_InputName_HelloWorldWithName() {
        String result = helloWorld.hello("Name");
        assertEquals("Hello World Name", result);
    }
```

## Import and Execute
It's a Gradle project, can be simply imported by any IDE such as Eclipse, Intellij.    
Firstly , ```git clone https://github.com/fengyuanyang/JavaTDD.git```    
Secondly, open with build.gradle file. IDE should do the rest of importing and dependencies download.    
Thirdly, open any test file you would like to execute, run it.     

## Background
As time goes by, project is getter big, people who wrote that code might have been missing.   
How could I refactor those code I don't even know why the logic like this.   
TDD is a perfect way for me to refactor or start the codes. What I need to do is trying my best to pass all the tests.
