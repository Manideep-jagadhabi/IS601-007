<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 1 - IceCream</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 10/23/2022 8:46:41 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-1-icecream/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216">https://gist.github.com/MattToegel/17d0ac833a03580d010ad92e83fc4216</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder IcecreamMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197420669-cd8188a8-a664-4faf-8c45-aff53ae668bb.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>calculate_cost logic<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197420679-30dedc16-8f99-401d-957c-f36a139a0edc.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>output screenshot that displays the value in currency format<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <div><br></div><div>To add up the cost of each choice I have iterated through the<br>Inprogress_icecream Array.&nbsp; &nbsp;</div>I used format function to return output in currency format.<br></td></tr>
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
<tr><td> <em>Response:</em> <p><span style="font-size: 13px;">OutOfStockException is handled by showing user that&nbsp; user selection is out_of_stock.<br>so please select from available options.</span><div><span style="font-size: 13px;">NeedsCleaningException is handled by showing user<br>that&nbsp; Icecream machine is used at maximum number of times .so it needs<br>to be cleaned at this point.</span></div><div><span style="font-size: 13px;">InvalidChoiceException is handled by showing user<br>that choice entered by the user is not valid, So please enter the<br>correct choice from options below.</span></div><div><span style="font-size: 13px;">ExceededRemainingChoicesException&nbsp;</span><span style="font-size: 13px;">&nbsp;</span><span style="font-size: 13px;">is handled by<br>showing user that you have used maximum number of scoops please select the<br>toppings to add now.</span><span style="font-size: 13px;"><br></span></div><div><span style="font-size: 13px;">InvalidPaymentException is handled by showing user<br>that Amount entered by the user is not matching to bill. so please<br>re-enter.</span><br></div><div><span style="font-size: 13px;"><br></span></div><div><span style="font-size: 13px;"><br></span></div><div><div><span style="font-size: 13px;"><br></span></div></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423482-118db720-84f5-43d0-a859-82d10fadbe82.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423485-2d1f0433-ceca-42a8-99ce-d866abe2d548.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423486-ffe68874-192a-49f6-81ed-0455334100ba.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 3<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423490-6ac52bc1-76c7-4e86-845e-493ba8fb83e3.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 4<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423493-c09faee3-6654-4fa1-8fd5-1c5f82214c50.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 5<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423527-cc111da6-c5bd-4d05-aff3-cfda020c80c5.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 6<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423532-76517b8d-5e22-4d3c-8652-214e5421916f.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 7<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197423534-8e8c1d94-5c93-4af7-8f47-44151836ed10.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 8<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/197424543-1dbd3aa6-dd07-41b7-b755-4ce04d8ed88f.PNG"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 1-8 passing<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <p>in Test 1&nbsp; &nbsp;testing first selection is container.<div>In Test 2&nbsp; testing we are<br>adding flavours only in case of stock availability.</div><div>In Test 3&nbsp; testing we are<br>adding Toppings only in case of stock availability.</div><div>in Test 4 testing&nbsp; add not<br>more than 3 flavours</div><div>Test 5 testing <span style="font-size: 13px;">add not more than&nbsp; 3<br>toppings</span></div><div>Test 6 testing&nbsp;<span style="font-size: 13px;">&nbsp;cost is&nbsp;</span><span style="font-size: 13px;">calculated properly based on the choices</span></div><div>Test<br>7 testing&nbsp;<span style="font-size: 13px;">Total Sales&nbsp; calculated properly</span></div><div>Test 8 testing&nbsp;<span style="font-size: 13px;">&nbsp;Total&nbsp;</span><span style="font-size: 13px;">icecreams<br>is properly incremented for each purchase</span></div><div>&nbsp;</div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/4">https://github.com/Manideep-jagadhabi/IS601-007/pull/4</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <p>No issues<div>I learnt how to create Test cases</div><div>I learnt how to handle exceptions&nbsp;</div><div>While<br>doing Exception Handling It is hard for me to do it in continued<br>flow during payment .</div><div>Later I figured it out how to resolve it</div><div><br></div><div><br></div><div><br></div><br></p><br></td></tr>
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