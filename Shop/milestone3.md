<table><tr><td> <em>Assignment: </em> IS601 Milestone 3 Shop Project</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 12/22/2022 11:27:16 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone-3-shop-project/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone3 branch</li><li>Create a new markdown file called milestone3.md</li><li>git add/commit/push immediate</li><li>Fill in the below deliverables</li><li>At the end copy the markdown and paste it into milestone3.md</li><li>Add/commit/push the changes to Milestone3</li><li>PR Milestone3 to dev and verify</li><li>PR dev to prod and verify</li><li>Checkout dev locally and pull changes to get ready for Milestone 4</li><li>Submit the direct link to this new milestone3.md file from your GitHub prod branch to Canvas</li></ol><p>Note: Ensure all images appear properly on GitHub and everywhere else. Images are only accepted from dev or prod, not localhost. All website links must be from prod (you can assume/infer this by getting your dev URL and changing dev to prod).</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Orders will be able to be recorded </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of the Orders table with valid data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209252149-f682a437-75b4-498e-bdb7-83d605a8fa6d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the Orders table with valid data<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of OrderItems table with validate data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209252269-0cbfc125-ee09-4698-ab65-add75bf98030.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of order items table with validate data in it<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the purchase form UI from Heroku</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209252698-679fd6af-e87f-440b-9ec1-cbc60662d298.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the purchase from UI<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a screenshot showing the items pending purchase from Heroku</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209253020-3a4824d2-934e-4129-99ab-173e380ac0d9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of showing the items pending purchase, total purchase price and a link<br>back to cart<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209263642-af10ec97-a113-469c-8547-ab3d0d32479a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing % price change to the user<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a screenshot showing the Order Process validations from the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209253808-094f194d-d168-41d2-8b27-5e8f22cbd89f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the Order Process validations for payment, address and zip code<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209254074-d6e50c7b-dd7d-4189-807d-e80b8e91ad6e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing the Order Process validations for paid amount vs cart amount,stock and<br>price of items<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add a screenshot showing the Order Process validations from the UI (Heroku)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209263836-9a11f8c2-cb92-403f-95f6-1c035deceb5c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the price difference message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209264634-16899e03-8c86-466f-8fa1-9a7b64f92f9b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing unavailable stock message<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209264740-14d10b94-eb0a-4b60-b62b-37a2ad5c5df9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot  shot showing invalid &quot;money received&quot; message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 7: </em> Briefly describe the code flow/process of the purchase process</td></tr>
<tr><td> <em>Response:</em> <div><ul><li>We have a button for checkout after adding items to the cart.</li><li>The same<br>cart details are pulled from the cart table and displayed as pending products<br>to be purchased on the checkout page after pressing the checkout button. Below<br>it, a shipping address form will be filled up.</li><li>Each item's quantity is tested<br>to see if it is within the stock on hand after providing the<br>necessary information and clicking on place order. If the product's cost in the<br>shopping cart matches the product's price in the database</li><li>To validate, the amount paid<br>is compared to the value stored on the cart server.</li></ul></div><br></td></tr>
<tr><td> <em>Sub-Task 8: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/21">https://github.com/Manideep-jagadhabi/IS601-007/pull/21</a> </td></tr>
<tr><td> <em>Sub-Task 9: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/checkout">https://is601-mj457-prod-2.herokuapp.com/checkout</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Order Confirmation Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot showing the order details from the purchase form and the related items that were purchased with a thank you message</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209265197-4d019203-9c30-424b-acdd-1167b08d8196.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the order details from the purchase form and the related items<br>that were purchased with a thank you message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how this information is retrieved and displayed from a code logic perspective</td></tr>
<tr><td> <em>Response:</em> <div>The cart details that are obtained for validation during the purchase are also<br>supplied to render on the order summary page.</div><div>The information was saved in an<br>array and sent to order summary for rendering when the order was confirmed<br>and the data was entered into the orders table.</div><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/21">https://github.com/Manideep-jagadhabi/IS601-007/pull/21</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/purchase">https://is601-mj457-prod-2.herokuapp.com/purchase</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> User will be able to see their Purchase History </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing purchase history for a user</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209265530-57c5b090-eef7-409a-99ff-a48e45268c63.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing purchase history for a user<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing full details of a purchase (Order Details Page)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209265803-a03bdae0-ec2b-41f1-b143-0f0259e96b02.png"/></td></tr>
<tr><td> <em>Caption:</em> <p> screenshot showing full details of a purchase (Order Details Page)<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the logic for showing the purchase list and click/displaying the Order Details</td></tr>
<tr><td> <em>Response:</em> <div>Upon clicking the view button, the user id specific order data saved in<br>the orders table are retrieved and shown with a button.</div><div>The order id is<br>supplied to the order page, and all of the information displayed on the<br>order summary page is retrieved by connecting the products and order items tables<br>for product details and for shipping data from the orders table.</div><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/21">https://github.com/Manideep-jagadhabi/IS601-007/pull/21</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/orders">https://is601-mj457-prod-2.herokuapp.com/orders</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Store Owner Purchase History </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing purchase history from multiple users</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209266645-3d94128b-5c3b-4796-955a-732e98d0c0f2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing purchase history from multiple users - two users with user name<br>manideep and admin can be seen<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing full details of a purchase (Order Details Page)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209266977-2f072802-2fbd-4213-a089-296aba8f5419.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot showing full details of a purchase made by admin<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the logic for showing the purchase list and click/displaying the Order Details (mostly how it differs from the user's purchase history feature)</td></tr>
<tr><td> <em>Response:</em> <p>While it largely resembles the user&#39;s purchase history feature, the user id filter<br>is not used when retrieving all of the users&#39; orders.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/21">https://github.com/Manideep-jagadhabi/IS601-007/pull/21</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/admin/orders">https://is601-mj457-prod-2.herokuapp.com/admin/orders</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the Cart page showing the button to place an order</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/209267439-823c3c74-0b51-4916-ad43-3ddd8eb6ef5c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of the Cart page showing the button to place an order<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe any issues and learnings throughout this milestone</td></tr>
<tr><td> <em>Response:</em> <p>By referring the&nbsp; sample SHOP project given in class , I learned what<br>should be included in server-side validations for a secure transaction.&nbsp; Faced issues while<br>fetching the order detail by clicking the view button. Resolved it&nbsp; by executing<br>a static query and debugging it in the database<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone-3-shop-project/grade/mj457" target="_blank">Grading</a></td></tr></table>