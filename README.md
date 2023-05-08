Download Link: https://assignmentchef.com/product/solved-project-1-grocery-store-inventory-cpsc-131
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Introduction</span>

Assume you’re writing software for a grocery store to maintain its inventory. You are provided a listing of items from the latest shipment to the store with each items name, quantity, price, and whether it is taxable or not. The store wants you to build a program that is able to store each grocery item in an internal list and ultimately calculate the potential revenue, tax revenue, and total revenue for the entire shipment.




<h1>Objective</h1>

You are given a partial implementation of two classes. GroceryItem​​ is a class that holds the information for each grocery item. GroceryInventory​​ is a class that holds an internal listing of GroceryItems​​         as well as the tax rate for the store. Your inventory could be 100 items it could be 9000 items. You won’t know until your program gets the shipment at runtime. For this you should use the vector class from the C++ standard library.




Complete the implementation of these classes, adding public/private member variables and functions as needed. You should choose an appropriate data structure to maintain this inventory with an unknown size known only at runtime. Your code is tested in the provided main.cpp.​

Initially the given code will not compile. As you complete the code, the tests should start to pass in main.cpp.​

<h1>Source Code Files</h1>

You are given “skeleton” code files with declarations that may be incomplete and without any implementation. Implement the code and ensure that all the tests in main.cpp​​    pass successfully.

<ul>

 <li>h​: This is to be completed</li>

 <li>h​: This is to be completed</li>

 <li>cpp​: The main function tests the output of your functions. This is already complete and should not change. You may wish to add additional tests. During grading your main.cpp file will be replaced with the one you were provided with.</li>

 <li>md​: You must edit this file to include the name and CSUF email of each student in your group. Do this even if you are working by yourself. This information will be used so that we can enter your grades into Titanium.</li>

</ul>




<h1>Hints</h1>

Start implementing the GroceryItem​​    class, then the GroceryInventory​​        class. As you write each class, test your code. main.cpp provides many of these tests already. Do not wait till the very end to test your code.

Names of items do not contain any spaces.




<h1>Obtaining and submitting code</h1>

We will be using GitHub Classroom to distribute the skeleton code and collect your submissions. This requires you to have an account on github.com. If you are new to GitHub, do the following to get started:

<ol>

 <li>Create an account at github.com. You may want to use this account to show a portfolio of your work to prospective employers in the future, so choose something professional.</li>

 <li>Read Understanding the GitHub Flow and Hello World at GitHub Guides.</li>

 <li>Read the instructions below for instructions on how to test.</li>

</ol>




Once you understand the basic operation of git, click the assignment link to fork your own copy of the skeleton code to your PC. One student from a group clicks on the link below and forms a new team. This student then invites his/her project partner as an “Outside collaborator” in the settings menu.




Do not fork your repository to your personal github account (instructors have admin access to private repositories under <u>https://github.com/CSUF-CPSC-131-Fall2018/</u><u>​  </u>)​ . Your code should have a URL like <u>https://github.com/CSUF-CPSC-131-Fall2018/project1-brians</u>​        ​, NOT <u>https://github.com/brian/project1-brians</u>​.




<a href="https://classroom.github.com/a/Ci2GcHVy">https://classroom.github.com/a/Ci2GcHVy</a>




Then edit your code locally as you develop it. As you make progress, commit and push your changes to your repository regularly. This ensures that your work is backed up, and that you will receive credit for making a submission. Don’t wait until the deadline to learn how to push code!




<h1>Testing</h1>

You can test how well your code is working by running the three test programs. Of course it is possible to compile and run each of these manually by hand, but this can become tedious. For that reason we have provided you with a testing script that automates the process, called critic.




critic is a Python 3 program that will work in the endorsed GNU/Linux environment. You can execute the ./critic command within your repository directory. With no arguments it prints out usage information:




$ ./critic

Usage:

critic &lt;COMMAND&gt;




Commands:




<table width="351">

 <tbody>

  <tr>

   <td width="96">build</td>

   <td width="255">compile and link</td>

  </tr>

  <tr>

   <td width="96">help</td>

   <td width="255">print this usage information</td>

  </tr>

  <tr>

   <td width="96">team</td>

   <td width="255">print team members</td>

  </tr>

  <tr>

   <td width="96">test</td>

   <td width="255">compile, then run unit tests</td>

  </tr>

 </tbody>

</table>




To attempt to compile all three test programs, use the ./critic build command:




$ ./critic build




To attempt to run all three test programs, use the ./critic test command:




$ ./critic test




We will use this process to test the functionality of your code while grading. We recommend that you try it out yourself ahead of time to confirm that your code works properly, or to get a feeling for how far from complete your work is.




<h1>Automated testing</h1>

We are also piloting the use of a continuous integration web service that automatically tests your code and gives real-time feedback. This service is provided courtesy of ​<a href="https://travis-ci.com/">Travis CI</a><u>​</u><a href="https://travis-ci.com/">.</a>




The Travis service will wait for you to push code to GitHub. After you do, it will try to compile and build your code. It will then send you an email describing the outcome. The email also has a link to a dashboard web page you can view to see a detailed log of what worked, or didn’t. This way you can get immediate objective feedback about how well your code is working. We recommend pushing your code to GitHub every time you reach a milestone and would like feedback on your progress.




You can check the results of automatic testing on Travis at ​<a href="https://travis-ci.com/">https://travis-ci.com/</a><u>​</u> (same login as your github account).