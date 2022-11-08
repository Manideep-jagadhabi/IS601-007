<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 1 - IceCream</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 11/7/2022 7:51:27 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-1-icecream/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216">https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder IcecreamMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197420669-cd8188a8-a664-4faf-8c45-aff53ae668bb.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>code for calculating the cost<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/200441347-592bcd13-02d6-4840-9da7-6b7ddd7f01cd.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>output of the Icecream machine calculating cost<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <div><br></div><div></div><div><br></div><div><p dir="auto" style="box-sizing: border-box;">Firstly we initialize the cost to 0&nbsp;</p><p dir="auto" style="box-sizing: border-box;">The<br>in-progress ice cream array is iterated over to add the cost of each<br>choice by using for loop&nbsp;</p><p dir="auto" style="box-sizing: border-box;">then we return the cost by<br>formatting the currency&nbsp; to decimal points by using :.2f.format() function.</p><div class="yj6qo"></div><div dir="auto" class="adL"<br>style="box-sizing: border-box;"><br style="box-sizing: border-box; color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;,<br>Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px; background-color: rgb(246,<br>248, 250);"></div></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Exception Handling </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of adjusted code to handle exceptions</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197421677-e7f5796d-6362-4ebe-a91f-c6905ba31201.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>shows out_of_stock_exception <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197421827-fd1a0d32-fd1a-4b7c-8760-7188d670bf21.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Invalid_choice_exception  is handled with proper user feedback <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197421832-d0dfe120-679e-4f66-8791-350d055185c3.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Exceeded_Remaining_Exception is handled with proper user feedback <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197421835-2e33910f-bb2b-40b3-9356-12f4e5fd0f36.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Invalid_payment_exception is handled with proper user feedback <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197422257-fceb3d66-3aab-43d9-ba87-825694e6b622.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Needs_cleaning_exception is handled with proper user feedback <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each exception handling process</td></tr>
<tr><td> <em>Response:</em> <p><span style="font-size: 13px;">OutOfStockException is handled by showing user that&nbsp; user selection is out<br>of stock. so please select from available options.</span><div><span style="font-size: 13px;">NeedsCleaningExceptinn is handled by<br>prompting&nbsp; that&nbsp; Icecream machine is used at maximum number of times .so it<br>needs to be cleaned at this point.&nbsp;</span></div><div><span style="font-size: 13px;">The user is also asked<br>to confirm if he/she would like to&nbsp;</span><span style="font-size: 13px;">proceed with the cleaning and<br>then continue selecting or else quit.</span></div><div><span style="font-size: 13px;">InvalidChoiceException is handled by prompting&nbsp; that<br>choice entered by the user is not valid, So please enter the correct<br>choice from options below.</span></div><div><span style="font-size: 13px;">ExceededRemainingChoicesExceptiom&nbsp;</span><span style="font-size: 13px;">&nbsp;</span><span style="font-size: 13px;">is handled by prompting<br>that you have used maximum number of scoops please select the toppings to<br>add now.</span><span style="font-size: 13px;"><br></span></div><div><div style=""><span style="font-size: 13px;">ExceededRemainingChoicesExceptions is handled&nbsp;</span><span style="font-size: 13px;">by prompting that<br>the maximum remaining choices have been reached, now proceed to</span></div><div style=""><span style="font-size: 13px;">the<br>next step. The user will also be moved to the next following&nbsp;</span><span style="font-size:<br>13px;">step( either topping or pay).</span></div></div><div><span style="font-size: 13px;">InvalidPaymentException is handled by prompting&nbsp; that &quot;Amount<br>entered by the user is not matching to bill. so please re-enter&quot;.</span><br></div><div><span style="font-size:<br>13px;"><br></span></div><div><span style="font-size: 13px;"><br></span></div><div><div><span style="font-size: 13px;"><br></span></div></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423482-118db720-84f5-43d0-a859-82d10fadbe82.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p> Test1- containers must be first selection<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423485-2d1f0433-ceca-42a8-99ce-d866abe2d548.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 2 - can only add flavors if they&#39;re in stock<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423486-ffe68874-192a-49f6-81ed-0455334100ba.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 3 - can only add toppings if they&#39;re in stock<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423490-6ac52bc1-76c7-4e86-845e-493ba8fb83e3.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 4 - Can add up to 3 flavors/scoops<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423493-c09faee3-6654-4fa1-8fd5-1c5f82214c50.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 5 - Can add up to 3 toppings<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423527-cc111da6-c5bd-4d05-aff3-cfda020c80c5.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 6 - cost must be calculated properly based on the choices (check<br>for currency format as part of this) <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423532-76517b8d-5e22-4d3c-8652-214e5421916f.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 7 - Total Sales (sum of costs) must be calculated properly (test<br>case should included a few icecream combinations/purchases)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423534-8e8c1d94-5c93-4af7-8f47-44151836ed10.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 8 - Total Icecreams should properly increment for each purchase<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197424543-1dbd3aa6-dd07-41b7-b755-4ce04d8ed88f.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 1-8 passing<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <div><span style="font-size: 13px;"><br></span></div><div><div style=""><span style="font-size: 13px;">Test 1 - verifing that the value of<br>currently_selecting is "Container" in the</span></div><div style=""><span style="font-size: 13px;">first selection.</span></div><div style=""><span style="font-size: 13px;">Test 2<br>- testing if a flavor quantity is equal to -1</span><span style="font-size: 13px;">&nbsp;when the<br>flavor is out of stock.</span></div><div style=""><span style="font-size: 13px;">Test 3 - testing if&nbsp;</span><span style="font-size:<br>13px;">a topping quantity is equal to -1 when the topping is out</span></div><div style=""><span<br>style="font-size: 13px;">of stock.</span></div><div style=""><span style="font-size: 13px;">Test 4 - testing if the remaining_scoops is<br>equal to 0 when&nbsp;</span><span style="font-size: 13px;">the maximum number of scoops is chosen.</span></div><div style=""><span<br>style="font-size: 13px;">Test 5 - testing if the remaining_toppings&nbsp;</span><span style="font-size: 13px;">is equal to 0<br>when the maximum number of toppings is chosen.</span></div><div style=""><span style="font-size: 13px;">Test 6</span><span style="font-size:<br>13px;">- testing if the cost is calculated properly based on the choices. The&nbsp;</span><span<br>style="font-size: 13px;">calculated cost is matched with the currency format of the actual cost<br>to&nbsp;</span><span style="font-size: 13px;">test formatting.</span></div><div style=""><span style="font-size: 13px;">Test 7 - testing if the total_sales<br>is calculated properly by matching it with the sum&nbsp;</span><span style="font-size: 13px;">of individual ice<br>cream costs.</span></div><div style=""><span style="font-size: 13px;">Test 8 - testing if the total_icecreams is properly<br>incremented</span></div><div style=""><span style="font-size: 13px;">After every purchase.</span></div></div><div>&nbsp;</div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/10">https://github.com/Manideep-jagadhabi/IS601-007/pull/10</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <div><br></div><div><div>I first considered handling exceptions in the file Icecream exceptions. Later, I understood</div><div>that<br>it should be handled in the Ice cream Machine file.</div><div>I gained knowledge about<br>how to manage exceptions and ensure good operation.</div><div>I also learned about Pytest and<br>how it functions as well as how it aids in the development</div><div>of better<br>programs.</div></div><div><br></div><div><br></div><div><br></div><div><br></div><div><br></div><div><br></div><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of successful output</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197424955-a87beee6-ed13-4b4d-b8f4-c6dbfe499bfa.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197424958-55fc6f53-b6f1-4ccf-bcdd-abe1c5f46282.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output 2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197424962-57b981cf-1581-4cac-95e2-8a349281263b.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output 3<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-1-icecream/grade/mj457" target="_blank">Grading</a></td></tr></table>