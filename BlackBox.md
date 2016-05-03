# What is Black Box Testing?

The functionality of the software under test (**SUT**) is checked without looking at: 
* the internal code structure
* implementation details 
* or knowledge of internal paths of the software.

> Based entirely on the software requirements and specifications.

Consider this 
![alt text][Black box]
[Black box]:  https://github.com/andy-appsumer/Testing/blob/master/blackbox.jpg "BlackBox Pic"
It can be any software system you want to test.

It can be:
- An operating system like Windows
- A website like Goole
- A database like Oracle
- Or even your own custom Application.

Input &#10230; ![alt text][Black box] &#10230; Output
you can test these applications by just focusing on the inputs and outputs without knowing their internal code implementation.

# Types of Black Box Testing
There are many types of Black Box Testing but following are the prominent ones.

#### 1. Functional Testing
This black box testing type is related to functional requirements of a system. It is done by software testers.

#### 2. Non-functional testing
This type of black box testing is not related to testing of a specific functionailty, but non-functional requirements such as performance, scalability and usability. 

#### 3. Regression Testing
Regression testing is done after code fixes, upgrades or any other system maintenance to check the new code has not affected the existing code.

# How to Peform Black Box Testing?
Generic steps followed to carry out any type of Black Box Testing.

1. Initially requirements and specification of the system are examined. 

2. Tester chooses valide inputs, (positive test scenario), to check whether Application Under Test processes them correctly. Also some invalid inputs (negative test scenario) are chosen to verify that the Application or system Under Test is able to detect them.

3. Tester determines expected outputs for all those inputs.

4. Software tester creates test cases with the selected inputs.

5. The test cases are executed.

6. Software tester compares the actual outputs with the expected outputs.

7. Defects if any are fixed and re-tested.

# Tools for Black Box Testing?
Tools for black box testing largely depends on the type of black box teting you are doing.

- For Functional/ Regression Tests you can use - QTP
- For Non-Functional Tests you can use - Loadrunner

Let's compare BlackBox with WhiteBox Testing?

> White Box Testing (Which is usually Unit Testing) validates internal structure and working of your software code, but the main focus of black box testing is validation of your functional requirements.

To conduct White Box Testing, knowledge of underlying programming language is essential. Current day software systems use a variety of programming languages and technologies and it's not possible to know all of them. 

> Black box testing gives abstraction from code and focuses testing effort on the system software behaviour. 

Usually, software systems are not developed in a single chunk, but is broken down in different modules. Black box testing facilitates testing communication amongst modules via Integration Testing. 

> In case you push code fixes in your live software system, a complete system check (black box regression tests) becomes essential.

Though White Box testing has its own merits and helps detect many internal errors which may degrade system performance. 
