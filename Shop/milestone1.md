<table><tr><td> <em>Assignment: </em> IS601 Milestone1 Deliverable</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 12/12/2022 9:05:59 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone1-deliverable/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone1 branch</li><li>Create a milestone1.md file in your Project folder</li><li>Git add/commit/push this empty file to Milestone1 (you'll need the link later)</li><li>Ensure your images display correctly in the sample markdown at the bottom</li><ol><li>NOTE: You may want to try to capture as much checklist evidence in your screenshots as possible, you do not need individual screenshots and are recommended to combine things when possible. Also, some screenshots may be reused if applicable.</li></ol><li>Save the submission items</li><li>Copy/paste the markdown from the "Copy markdown to clipboard link" or via the download button</li><li>Paste the code into the milestone1.md file or overwrite the file</li><li>Git add/commit/push the md file to Milestone1</li><li>Double check the images load when viewing the markdown file (points will be lost for invalid/non-loading images)</li><li>Make a pull request from Milestone1 to dev and merge it (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku dev</li></ol></li><li>Make a pull request from dev to prod (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku prod</li></ol></li><li>Submit the direct link from github prod branch to the milestone1.md file (no other links will be accepted and will result in 0)</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Feature: User will be able to register a new account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207129235-f3b8983d-5e68-4689-8d52-63ce60bcb636.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing invalid email and password validation<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207129472-25625c52-9ad0-4385-8ceb-06b76d9e3343.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing passwords do not match validation <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207132007-5ad651b0-bba6-4cbd-ab8c-6a18b30e796f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing username not available validation<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207133166-c139a550-a58c-4c41-8d6f-429fb4bc63b5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the form with valid data filled in before the form is<br>submitted<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207131204-bb8bfa9d-cd12-465a-8836-21d74a62b2d0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing not valid email address<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Users table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207137904-31302205-7f1c-460c-95c4-a685f3046c7a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of showing the valid user data from task1. Clearly highlighted which row<br>it is<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>1.Each field in the form has its own validation, which is handled by<br>wtforms. The form can only be successfully submitted once all the fields have<br>been filled out.<div>2.Validation is done with the help of wtforms validators. The following<br>validators are used: DataRequired() is used to mark the field as required, EqualTo()<br>is used to check if the password and confirm-password match and Email() is<br>used to check for valid email format. Username is checked to match **(a-20-9_-]<br>(2,30)S&quot; this regex. Duplicate username and email values are checked during the inserting<br>into the database. A flash message is populated for a duplicate entry exception.</div><div>3.A<br>bcrypt hash of the password is performed before it is stored in the<br>database.</div><div>4.The users table, which is created in the database along with the created<br>and changed timestamps, contains all of the form data.</div><div><br></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Feature: User will be able to login to their account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207148106-37510bd4-51f0-43d0-833e-237a96a150a6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing password mismatch validation<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207148600-6936bbde-cdda-488e-8f3e-ef2281401529.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot Showing non-existing user validation<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of successful login</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207183694-19337551-4093-415d-b11d-b43398201c3b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot Showing Successful login<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>1.Each field in the form has its own validation, which is handled by<br>wtforms. The form can only be successfully submitted once all the fields have<br>been filled out.<div>2 Validation is done with the help wtforms validators which work<br>for both front-end and back-end. The &quot;Email or Username&quot; field accepts either email<br>or username and is validated based on the input. If the username or<br>email is not present in the database then a flash message saying &quot;Invalid<br>User&quot; is displayed. If the username matches but not the password then a<br>flash message saying &quot;Invalid Password&quot; is displayed.</div><div>3&nbsp;&nbsp;The hashed password that is already stored<br>in the database is compared to the entered password.A function bcrypt.check_password_hash() does this<br>matching with the help of salt value.</div><div><br><div><br></div></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Feat: Users will be able to logout </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the successful logout message</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207164842-22c6b7c0-f042-4fb7-a30a-cda11fe913a1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing about being logged out<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the logged out user can't access a login-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207170573-da16e607-c110-4b2c-bc18-999fde6298a4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the logged out user can&#39;t access a login-protected page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>When the user logs in, the user object is stored in the session.<br>When the page reloads, that User object in the session is used to<br>authenticate instead of calling the database. Which helps in avoiding the overhead. If<br>the User object is not present in the session then it loads from<br>the database.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Feature: Basic Security Rules Implemented / Basic Roles Implemented </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the logged out user can't access a login-protected page (may be the same as similar request)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207171922-9eb099ec-0197-42ca-91c3-5e9441efd0f2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the logged out user can&#39;t access a login-protected page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing a user without an appropriate role can't access the role-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207172340-425df476-eed1-4a5f-b4ce-c37d33e69e5d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing  a user without an appropriate role can&#39;t access the role-protected<br>page Checklist<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Roles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207172752-1745e827-36f8-433b-abfd-935361588819.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of roles table with valid data<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a screenshot of the UserRoles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207184422-3c5509b9-ee7c-478b-9536-11cf43cc6103.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the UserRoles table with valid data. <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add the related pull request(s) for these features</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Explain briefly how the process/code works for login-protected pages</td></tr>
<tr><td> <em>Response:</em> <div>The @login_required decorator provided by flask_ login protects pages that require logins. Every<br>time a page request is made, this triggers the user loader. The user<br>will be loaded from the session if exists to avoid repeated database calls.<br>If not present in the session then it loads from the database.<br></div><br></td></tr>
<tr><td> <em>Sub-Task 7: </em> Explain briefly how the process/code works for role-protected pages</td></tr>
<tr><td> <em>Response:</em> <div>Flask principal is used to safeguard role-protected pages. We define permission together with<br>the position required for it. By adding the permission decorators before the desired<br>pages, this permission can be added. With the user name and authentication type,<br>the identity is loaded into the session.</div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Feature: Site should have basic styles/theme applied; everything should be styled </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots to show examples of your site's styles/theme</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207184876-50677d1e-c292-481b-ae91-241771167c97.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing styles and navigation and register form. All the forms follows the<br>same theme.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207206159-120017f6-aa57-4edd-8acd-4f3021a9efa7.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing styles of tables<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain your CSS at a high level</td></tr>
<tr><td> <em>Response:</em> <p>adopted a gloomy theme for the website. Select a sample navigation from bootstrap<br>where the login, register, and logout buttons are offset to the right of<br>the main navigation. To ensure that the text fields will fit within the<br>required length, select a card layout for all of the forms. I&#39;ve provided<br>a few inline styles for the filter&#39;s order and the roles layout. By<br>using inline styling, applied custom colors. used marquee tag as well.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Feature: Any output messages/errors should be "user friendly" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of some examples of errors/messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207172340-425df476-eed1-4a5f-b4ce-c37d33e69e5d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing a user without an appropriate role can&#39;t access the role-protected page<br>Checklist<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207171922-9eb099ec-0197-42ca-91c3-5e9441efd0f2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the logged out user can&#39;t access a login-protected page<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207132007-5ad651b0-bba6-4cbd-ab8c-6a18b30e796f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing username not available validation<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a related pull request</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you made messages user friendly</td></tr>
<tr><td> <em>Response:</em> <p>I have designed different pages with unique and user-friendly messages that are presented<br>for the HTTP server error messages like 401, 403, and 404. Any of<br>those issues will cause a redirect to the appropriate HTML page to be<br>rendered. I took the field name from the exception message and flashed a<br>message saying it wasn&#39;t available for duplicate entry instances that happened for username<br>or email.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> Feature: Users will be able to see their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207192829-4c81a35c-ec9e-4cf9-8984-b63e4d15de03.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshots of the User Profile page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Explain briefly how the process/code works (view only)</td></tr>
<tr><td> <em>Response:</em> <p>The user id is retrieved from current user and shown on the profile<br>page when it loads. With that user id email and username of that<br>user is fetched from the database and is populated to the respective fields<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Feature: User will be able to edit their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page validation messages and success messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207194648-1c172b69-f8cb-433d-a335-34b96db0daef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshots of the username and email validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207196794-9eb0ec28-722c-4b88-a90c-7f7dd8922f5d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of the password validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207197201-b4d50886-a76f-4def-9181-275a2a38fbe1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of password mismatch message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207197582-a4715aad-ed4a-4c23-b965-a2471538cc34.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of choosen username is not availabe validation message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207197917-61013da3-ef6a-4815-aa83-165a9192b0fc.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing email already in use<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add before and after screenshots of the Users table when a user edits their profile</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207198373-796caee7-7361-4706-ac8d-a37673aaa39b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the users table before editing profile<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/207198612-9a25150a-8604-4532-b911-e8bbcd0af079.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Username &quot;manideepbenny&quot; updated to &quot;manideepjagadhabi&quot;<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/14">https://github.com/Manideep-jagadhabi/IS601-007/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works (edit only)</td></tr>
<tr><td> <em>Response:</em> <p>For each update request, the fields for the username and email are updated.<br>They made sure the username and email values adhered to the necessary standards<br>for each before altering them. If the answer is yes,&nbsp; &nbsp;checks to see<br>if any of of the variables have already been utilized by another user<br>of the database. If the answer is true, a flash message indicating that<br>the particular value is not available for use. In order to update a<br>password, we first check to see if the new password matches the confirm<br>password, and then we see if the current password matches the password that<br>is already in the database. The password is updated if all of these<br>criteria are met.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe any issues and learnings throughout this milestone</td></tr>
<tr><td> <em>Response:</em> <div>jinja2.exceptions have been encountered. UndefinedError: "flask login.mixins. AnonymousUserMixin object has no attribute "has<br>role"" appears while looking for the user role to fill in the user-specific<br>navigation link for the admin. I realized that the problem was being caused<br>by the fact that I was checking for the current user before determining<br>whether the user was authenticated. Added an authentication check before examining the role<br>to fix the issue. I attempted to submit the user object to the<br>wtforms with form.process() so that it could be filled with data, but I<br>quickly understood that the User object cannot be iterated. So it was changed<br>back to the traditional assigning method.</div><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Prod Application Link to Login Page</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/login">https://is601-mj457-prod-2.herokuapp.com/login</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone1-deliverable/grade/mj457" target="_blank">Grading</a></td></tr></table>