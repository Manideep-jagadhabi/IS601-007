<table><tr><td> <em>Assignment: </em> IS601 Mini Project 2  Business Management</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 12/5/2022 10:06:33 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-2-business-management/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>checkout dev and pull any latest changes</li><li>Create a branch called MiniProject-2</li><li>Add all the baseline files first under a folder called BusinessManagement (included below)</li><li>Don't forget to copy your .env file from flask_sample into BusinessManagement</li><li>source the venv and pip install the requirements.txt</li><li>Run the BusinessManagement/sql/init_db.py script</li><li>Immediate add/commit/push to github</li><li>Open a pull request and keep it open until you're done adding the submission file</li><li>&nbsp;(optional) updated the deploy dev yml file and add MiniProject-2 so you can deploy to dev without needing to merge into dev</li><li>Make your code changes per the following requirements</li><ol><li>Important: run the test files indiviudally as you're working/testing to save on query quota usage</li></ol><li>Add/commit periodically (recommended after you implement a TODO item or checlist item)<br></li><li>Anywhere relevant add your ucid and the date you added the code (best to do this as you go)</li><li>You'll be capturing website screenshots from dev and code snippet screenshots (ensure you upload these properly as pull request comments to the pull request from step 5</li><ol><li>Note: You don't need separate screenshots for each checklist item, when possible it's recommended to try to capture multiple items together</li><li>Ensure all screenshots are properly captioned in the deliverable section</li></ol><li>You may save your progress when filling out this submission as often as you want</li><li>Once done, copy the markdown or download the md file and save it under the BusinessManagement folder</li><li>Do a final add/commit/push</li><li>Verify everything looks ok in the pull request</li><li>Merge the pull request</li><li>Make a new pull request from dev to prod and merge it</li><li>Navigate to the submission file under the BusinessManagement folder</li><li>Copy the github url to the exact file and submit it to Canvas</li></ol><div>You'll be implementing a basic Business Management site.</div><div>There will be some provided files fully working as-is and some skeleton files you'll need to fill in.</div><div>The files you need to fill in will have TODO items or comments mentioning what's expected.</div><div>There are provided test case files too that all must be passing for full credit. Do not edit these test case files.</div><div>The site will handle CRUD operations for Companies and Employees as well as allowing import of Company/Employee data via a csv file.</div><div><br></div><div>Baseline files:&nbsp;<a href="https://github.com/MattToegel/IS601/tree/F22-MiniProject-2">https://github.com/MattToegel/IS601/tree/F22-MiniProject-2</a></div><div>May want to download branch as a zip, then copy/paste the files into your repo</div><div><br></div><div>Provided files you don't need to edit:</div><div><ul><li>000_create_table_companies.sql</li><li>001_create_table_employees.sql</li><li>db.py</li><li>init_db.py</li><li>flash.html</li><li>company_dropdown.html</li><li>country_state_selector.html</li><li>upload.html</li><li>sort_filter.html</li><li>all test files</li><li>geography.py</li><li>__init__.py (remains empty)</li><li>Dockerfile</li><li>main.py</li><li>index.py</li></ul><div>All other files likely have requirements to fill in.</div></div><div><br></div></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Identity Edits and Setup </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the index page being displayed (from dev)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205559434-43e7af4b-ec86-4bfd-9290-506d2413f2e3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of index page being displayed from dev<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot from the DB extension of vs code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205569062-0034378f-f015-4d9b-a15d-d992d0514c1f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of IS601_MP2_Companies table from DB extention of vscode<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205569413-29b017c7-1b86-4dde-93af-7bc0f0c6220c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of IS601_MP2_Employees table from DB extention of vscode<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Upload / Import CSV File (provided data.csv) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of /import route</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205537432-5121308f-1b41-48f0-828b-4a99842ae53f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added screenshot of checking if the file is a .csv file otherwise reject<br>with a flash<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205539186-556aebce-6292-4dff-aa16-1f1ff8d5b990.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for CSV file should be read from the provided stream as<br>a dict<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205539396-08196fbc-ef77-4c2f-adeb-54f35210ffc9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for Extracted employee data should be append as a dict to<br>the employee list<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205539613-7346ab68-a335-460d-9315-a98efdf812c4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for  Extracted company data should be appneded as a dict<br>to the comapny list<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205539840-7b33b85e-794f-4f2d-a36a-0846f109ff64.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for After each query a flash message should be generated noting<br>how many records were processed<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205541166-f8bd690b-8601-4b4e-9ce3-615fdc9031e8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for If a particular list was empty a flash message should<br>note that the particular list wasn&#39;t loaded or was empty<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of the website when uploading the data.csv file</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205566377-c9800684-35d6-45bf-984b-8e9008479635.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the flash message rejecting  a file which is not of<br>type .CSV<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205568507-9c597d5d-eb56-4fab-a0b9-e621c5c0848b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the error message when the form was submitted without a file<br>attached<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205743129-be5ae884-2d50-4331-a7c1-c55c93022e7d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the .CSV file inserted successfully<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data (basic summary/view)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205787688-612ff29e-aa5a-41a0-9f3a-a435f20762fd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screen shot of some employee data uploaded<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205787946-336f6ad7-c9d3-45fb-ae8f-b3266be2de60.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of Company data was uploaded<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Add Employee </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /add route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205542015-b2f99324-a2ad-4434-aefb-073ddc363854.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to retrieve first_name, last_name, company (id), email<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205542787-3e92e6d1-8907-43a8-a98f-33c8a6b1cc89.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for first name,last_name,email,company is required otherwise message will be flashed<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205543175-e813ba05-84ea-47fd-a66e-b3bd1525a651.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for Proper INSERT query should be visible,Except block should have a<br>user friendly message flashed and a print() of the exception<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for add employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205575662-72c3228e-ed8c-4103-b1be-9ed2ab68aeaf.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Add Employee From Filled in valid data prior to submission<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205576940-56108fd3-8623-4b7c-a048-5f0438086d3e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>success flash message for adding employee record<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205578235-f91a4f5b-0d14-4bdb-a95b-1f39c5f86bea.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>first_name error message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205578647-71e3e6bf-44e3-48c3-ad6f-a31e26b55cbb.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>last_name error message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205579095-a9dfd6dc-d712-4365-8024-810ebf987d7c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Email error message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of new employee DB record from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205788248-602fa0fa-929c-4ec8-b872-48910cfe3b08.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of new employee DB record<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> List/search Employees </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /search route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544247-76d3e2f2-c7f0-43f3-a42f-133fbfa5209b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to SELECT query that should be filled in properly to pull<br>employ id, first_name, last_name, email, company_id, company_name via a LEFT JOIN<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544320-5b6ad6c6-6fed-47a5-8238-8513a3b503ff.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to Check request args for fn, ln, email, company, column, order,<br>limit (exact naming is required)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544401-6c1bd09b-89d1-43a2-8348-c33d3f31d4e5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to append like filter for first_name if provided,append like filter for<br>last_name if provided,,append like filter for email if provided<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544640-2c38e74d-27f4-4101-9a31-1e537607f998.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to append equality filter for company_id if provided,append sorting if column<br>and order are provided and within the allowed columns and order options (asc,<br>desc) allowed_columns = [&quot;first_name&quot;, &quot;last_name&quot;, &quot;email&quot;, &quot;company_name&quot;]<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544754-e408fe5e-0f18-4ce6-9f6e-8a4bae9a1001.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to append limit (default 10) or limit greater than 1 and<br>less than or equal to 100<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544843-6cd0f797-6825-4bcc-aba1-ecd71b82adb2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to provide a proper error message if limit isn&#39;t a number<br>or if it&#39;s out of bounds<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205544953-5d4bcc40-f4a4-46bf-880b-527fc6eebd2d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to Except block should have a user friendly message flashed and<br>a print() of the exception<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for search employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205749176-551b7118-be8a-4e18-ba98-61b36cda688a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>first_name filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205749937-c6ceeae5-ce62-41d3-901e-80270c09e487.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>email_filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205750717-7251ee9a-fdc9-418c-87bc-c21932ad039e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>last_name filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205750970-123ae8bd-a08f-4aa7-899a-235332d657bd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>company_filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205752430-ee403923-f63c-49e9-b9f4-c535538ae832.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>ascending_filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205752712-13e14268-57ed-4b97-9ec6-44756c91a857.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>descending_filter<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Edit Employee </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /edit route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205793519-dce0de89-3b50-4b9c-a8ed-7e660fc71ec6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code retrieve id (from request args) first_name, last_name, company (id), email from<br>form<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205545879-393b1ee3-efeb-4e57-a2b0-f9c842e3608b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to first_name is required (flash proper error message),last_name is required,company doesn&#39;t<br>require a flash and may be empty/None, (flash proper error message),email is required<br>(flash proper error message)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205546139-ed65960d-c811-414c-bc71-5bd03d6722da.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to Proper UPDATE query should be visibility,	Except blocks (two) should have<br>a user friendly message flashed and a print() of the exception,,Proper SELECT query<br>should be visible,,Employee data should be passed to the render_template()<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for edit employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205591390-fd450b56-0b81-4fa2-bf7a-89f53e80719d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Employee record in the page before an edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205592007-94628f6e-db00-45e5-9cc9-345a02249228.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>data before an edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205592859-ec9bdc4c-956d-418a-85bb-4440e7db5614.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>data after an edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205593326-be30e139-e923-4cc4-abfe-041aaa920372.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Employee record in the page after an edit<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data before and after of employee data edit from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205788839-8a48d13a-8482-46c4-8b1c-fc2d75ec69b8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Data Before Edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205788987-ecc53182-4120-4b81-a274-55724957dea8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Data After  Edit<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Add company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /add route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205761260-a85dd1c6-4345-4c3f-ae8b-7c7e2d9285be.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code to  retrieve form data for name, address, city, state, country,<br>zip, website<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205761596-e33c7eac-f4cd-404d-9723-537e44ce7bee.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for name,address,city required  (flash proper error message)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205762478-bf08ec64-1ed6-4eb8-a281-2ffb29498e25.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for state,country Required and Website is not<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205763146-2e63ab0a-8213-4674-a6ba-6d1632a5e727.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added code for Proper INSERT query ,Except block  user friendly message <br>and a print() of the exception<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for add company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205790568-ed316349-0e6d-4b6e-b503-3c177ce8aa83.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>filled data prior submission<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205790804-f6008658-6f8a-4b6e-8cdd-0ebb4b88a698.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>successfully added company<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205755182-c103e3bb-f9ab-4bd9-85a8-e2e17787efb3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>name error<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205755521-a7a7e12b-6d41-4c3d-b5b6-2c7d5b3cbf6a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>address error<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205755897-6126211e-adc3-4e32-903c-d3e9ee7188fc.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>city error<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205756262-b1f2a5d9-63af-4570-bdfc-a621f3767123.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>country error<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205756523-5da25074-eb9f-42b5-aeb4-65a10a269601.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>state error<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of new company DB record from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205790913-5a8e0e52-c149-4f5f-9397-024ea555b234.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Valid Comapany data <br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> List/Search Comapny </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /search route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205547175-729a5bfe-4285-4bf3-9e19-1fc105be2134.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>SELECT query should fetch id, name, address, city, country, state, zip, website, employee<br>count for the company (likely a sub-query is needed)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205547278-66411dd0-8908-4e54-ba25-a54bc34a1584.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Check request args for name, country, state, column, order, limit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205547722-ce03918f-32c7-43ac-9a6b-b8c4a4e7ae39.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Append a LIKE filter for name if provided, Append an equality filter for<br>country if provided, Append an equality filter for state if provided,	Append sorting if<br>column and order are provided and within the allows column and allowed order<br>asc,desc allowed_columns = [&quot;name&quot;, &quot;city&quot;, &quot;country&quot;, &quot;state&quot;],append limit (default 10) or limit greater<br>than 1 and less than or equal to 100,provide a proper error message<br>if limit isn&#39;t a number or if it&#39;s out of bounds, Except block<br>should have a user friendly message flashed and a print() of the exception.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for search company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205757820-099a25fb-5a79-4ea6-b4c3-56fcd53b8049.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Results with name filter applied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205759278-abd0e7a6-34ad-4dce-8d93-af978aac6577.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Results with Country Filtered<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205759492-6e429222-746d-4928-8cfc-7d61fb40963e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Results of state filter applied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205760049-67b36aba-4575-4ede-952b-b6ec385b51c6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Ascending_filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205760357-d63bef6f-23a1-45b9-9573-61b1964a2cfd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Desending_filter<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Edit Company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /edit route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205552028-0a7c0302-e4e3-41a2-a791-1914505aaa7a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code should retrieve id (from request args) name, address, city, state, country, zip,<br>website from form<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205551909-d4c84577-1c9a-4daf-ad03-8dcb5c6bb661.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>name is required (flash proper error message)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205552175-d6d81ae7-6cfd-4557-8f0b-e6ad27c3f7a0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>address is required (flash proper error message),city is required (flash proper error message),	state<br>is required (flash proper error message),country is required (flash proper error message) Proper<br>UPDATE query should be visible,Except blocks (two) should have a user friendly message<br>flashed and a print() of the exception,	Proper SELECT query should be visible,Company data<br>should be passed to the render_template()<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for edit company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205791855-c5801719-1585-45c7-a6ef-a162f70981f2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Data Before edit<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205792173-2b448100-9844-4d3d-99fe-3401138a7621.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Data After edit<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data before and after of company  data edit from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205792382-da407bb1-55e1-4ab7-bc93-b54d11446344.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Initially Name of the city was Chicago As Shown in Screen shot<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205792642-6edff4f5-c382-4691-861c-fd81849797ca.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Chicago is Changed to Newark here After edit<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Delete Employee and Delete Company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /delete route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205549697-89f059cf-0d4a-4be3-8822-468a8ce608a3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Delete employee by id,Redirect to employee search,	All request args (minus id) are passed<br>to the redirect route,Success message should be flashed if the process worked<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a before and after website screenshot of deleting an employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205785648-3d924864-79ad-4b0c-bcf3-ef6f6a5b04e6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot before deleting an employee<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205785939-3c8d7b4d-03a4-40c4-acf0-13c86d063b26.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot after deleting an employee<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of code for /delete route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205549269-07353c11-a351-4b40-9e78-7f61898ce656.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Delete company by id,Redirect to company search,	All request args (minus id) are passed<br>to the redirect route,	Success message should be flashed if the process worked<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a before and after website screenshot of deleting a company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205786867-2eccebab-ffe5-4a55-bb0c-311bdd858f8f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot before deleting a company<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205787130-cc6d6021-d94c-4364-a10f-0b323ca5d377.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot after deleting company<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 10: </em> Test Cases and Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot Test case Results</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/205792859-2ea5c44d-19cc-4ab7-8530-fff2f4e8b489.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test Cases<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Issues / Learnings / Interesting things to note</td></tr>
<tr><td> <em>Response:</em> <p>i have learned how to handle GET and POST calls to perform actions<br>like edit,sort, and delete. learned how to use Wtforms and pass arguments to<br>it.Learned how to handle exceptions and flash messages<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-mini-project-2-business-management/grade/mj457" target="_blank">Grading</a></td></tr></table>