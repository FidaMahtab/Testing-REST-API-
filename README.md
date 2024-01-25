# Testing-REST-API-
Testing REST API of an Employee Management System, built in Java spring boot and ReactJS<br>
The project can be found here : https://github.com/ZahidHaque/TeamTracker

<h3> Use Case Diagram</h3>
<img src = "UML Diagram/Activity_Diagram.png">

<h3>Create API </h3>


<b> Findings:</b> 
<ul>
<li>If we post one extra column like “address” that will declare as an error, and it says “bad request” </li>
<img src= Images/1.png>

</ul>


<b> Improvement:</b> 
<ul>
<li>User must be filling all the data given so that it will send no errors. </li>
<img src= Images/2.png>
</ul>

<h3>Get API </h3>

<b> Findings:</b> 
<ul>
<li>If we try to find such ID which was not exist or negative values which is not possible in numeric format in our database that will show “Not Found” error.</li>
<img src= Images/3.png>
</ul>

<b> Improvement:</b> 


<h3>Get all API </h3>
<b> Findings:</b> 


<b> Improvement:</b> 
<ul>
<li>If the database is totally clear, there should be a pop-up message. </li>

</ul>

<h3>Update API </h3>

<b> Findings:</b> 

<b> Improvement:</b> 
<ul>
<li>If database update successfully there should be a message pop-up. </li>
<img src = Images/4.png>
</ul>

<h3>Delete API </h3>

<b> Findings:</b> 

<b> Improvement:</b> 
<ul>
<li>If the row of database successfully deleted, there should be a pop-up message and mention which row was deleted. </li>
<img src = Images/5.png>
</ul>
