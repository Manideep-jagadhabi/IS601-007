<table><tr><td> <em>Assignment: </em> IS601 Milestone 2 Shop Project</td></tr>
<tr><td> <em>Student: </em> Manideep Jagadhabi (mj457)</td></tr>
<tr><td> <em>Generated: </em> 12/22/2022 7:30:11 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone-2-shop-project/grade/mj457" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone2 branch</li><li>Create a new markdown file called milestone2.md</li><li>git add/commit/push immediate</li><li>Fill in the below deliverables</li><li>At the end copy the markdown and paste it into milestone2.md</li><li>Add/commit/push the changes to Milestone2</li><li>PR Milestone2 to dev and verify</li><li>PR dev to prod and verify</li><li>Checkout dev locally and pull changes to get ready for Milestone 3</li><li>Submit the direct link to this new milestone2.md file from your GitHub prod branch to Canvas</li></ol><p>Note: Ensure all images appear properly on github and everywhere else. Images are only accepted from dev or prod, not local host. All website links must be from prod (you can assume/infer this by getting your dev URL and changing dev to prod).</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Users with admin or shop owner will be able to add products </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of admin create item page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208785169-dbd4e966-1bda-43d2-bfcc-f6b2528b523a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of admin create item page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot of populated Products table clearly showing the columns</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208785615-11c375ac-23c7-4934-bc39-1dd719755738.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of populated Products table clearly showing the column<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly describe the code flow for creating a Product</td></tr>
<tr><td> <em>Response:</em> <div>&nbsp;• I verify that an id is present in the arguments after the<br>form has been filled out correctly and submitted to determine whether it was<br>an edit or create action. If no id, the server validation is&nbsp; &nbsp;<br>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;done with the validate_on_submit function.</div><div>• After the<br>information has been verified, it is all entered into the database and a<br>confirmation message is flashed.</div><div>• If a mistake happens, the appropriate message flashes.</div><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/admin/product">https://is601-mj457-prod-2.herokuapp.com/admin/product</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Any user can see visible products on the Shop Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of the Shop page showing 10 items without filters/sorting applied</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208812422-0828189c-c98c-4d3e-a192-e5376c4b003b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the shop page showing first 5 items without filters applied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208812499-1317f2ae-af21-41b6-a41f-0818d865466d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the shop page showing next 5 items without filters applied<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Shop page showing both filters and a different sorting applied (should be more than 1 sample product)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208812715-6c75a96e-0812-4cc5-af36-a802348745b7.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing Shop page showing both filters and a different sorting applied<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the filter/sort logic from the code</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208789878-3124d593-f255-4317-ab33-08107f512d42.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of the filter/sort logic from the code<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Briefly explain how the results are shown and how the filters are applied</td></tr>
<tr><td> <em>Response:</em> <div>• The category list dropdown is created when a page loads by adding<br>up all of the category types that are present in the database.</div><div>• Then,<br>if any of the filters are chosen, the corresponding filters are added to<br>the fetching query.</div><div>• All the products are fetched from the database with filters<br>applied if any whose stock is greater than 0, and visibility is set<br>to true</div><div>• If there is a problem retrieving products, a message is flashed.</div><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/shop">https://is601-mj457-prod-2.herokuapp.com/shop</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Show Admin/Shop Owner Product List (this is not the Shop page and should show visibility status) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of the Admin List page/results</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208790947-8ed806ca-c710-46c6-a171-9381a7fea106.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of Admin/Shop Owner Product List page with non visible product highlighted<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the results are shown</td></tr>
<tr><td> <em>Response:</em> <div>•&nbsp; All product information, even that of hidden components, is retrieved. In the<br>query logic, visibility is marked as true if 1 and false otherwise.</div><div>• Table<br>helper.html is used to render the retrieved products.</div><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/admin/product/list">https://is601-mj457-prod-2.herokuapp.com/admin/product/list</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Admin/Shop Owner Edit button </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the edit button visible to the Admin on the Shop page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208791505-01b2f52a-b783-4241-adf7-c6ca531fc517.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of  showing the edit button visible to the Admin on the<br>Shop page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the edit button visible to the Admin on the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208791905-cc8312c3-fb12-421b-86c0-41fb72279728.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot  showing the edit button visible to the Admin on the Product<br>Details Page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot showing the edit button visible to the Admin on the Admin Product List Page (The admin page)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208792158-b91d8ef3-833c-4214-b75b-b230e0d56aaf.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the edit button visible to the Admin on the Admin Product<br>List Page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a before and after screenshot of Editing a Product via the Admin Edit Product Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208792501-749ec2db-fac1-45ea-8198-7f96ff21650a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing Editing a Product via the Admin Edit Product Page<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208793049-011250bf-14dd-4b97-a2b3-c5007389b6f9.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing After Editing  Product stock<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208793651-8347bd59-beb3-4708-9370-09b259302f8a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of admin edit page after Editing<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Briefly explain the code process/flow</td></tr>
<tr><td> <em>Response:</em> <div>• The edit page accepts an id as a parameter and preloads its<br>details in the form.</div><div>• All the values are changed in the database with<br>an update query after changing the values and clicking "Edit Product."</div><div>• When the<br>operation is successful or unsuccessful, a message flashes.</div><br></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 7: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/admin/product/list">https://is601-mj457-prod-2.herokuapp.com/admin/product/list</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Product Details Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the button (clickable item) that directs the user to the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208807505-01ccc6bd-acfa-41d0-8f56-4ffee079db6f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot showing the clickable item that directs the user to the product Details<br>Page. Here the Highlighted title is clickable<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the result of the Product Details Page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208807705-f8f9902d-54f1-47f8-b312-a98ac13cd090.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot Showing the result of the Product Details Page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the code process/flow</td></tr>
<tr><td> <em>Response:</em> <div><br></div><div>• The product details page loads when the product title on the shop<br>list page is clicked, and the matching id is supplied as an argument.<br></div><div>•<br>The product's id and all of its details are retrieved from the database<br>using parameters.</div><div>•&nbsp; These details are populated in a horizontal card layout.</div><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add a direct link to heroku prod for this file (can be any specific item)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/admin/productDetails?id=1">https://is601-mj457-prod-2.herokuapp.com/admin/productDetails?id=1</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Add to Cart </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of the success message of adding to cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208807927-0537f76e-d1fa-484c-be14-e02a09c18c36.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the success message of adding to cart<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the error message of adding to cart (i.e., when not logged in)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208797146-b1c4d059-21dd-496d-b509-03e1bebd2046.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the error message of adding to cart when not logged in<br><br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Cart table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208807927-0537f76e-d1fa-484c-be14-e02a09c18c36.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of cart table from UI<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208808575-a389f3e4-a61d-478e-aab6-7fa034859d4a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the Cart table from database<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Tell how your cart works (1 cart per user; multiple carts per user)</td></tr>
<tr><td> <em>Response:</em> <p>Each user has a single cart in which they can add multiple things.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Explain the process of add to cart</td></tr>
<tr><td> <em>Response:</em> <div>• The product's matching id and quantity are sent to the cart route<br>when a user clicks the "+Add" button to add a product to the<br>cart.&nbsp;</div><div>• Cart adds the user id, cost, quantity, and product id to the<br>cart table.</div><div>•If the item is already in the shopping basket, the quantity is<br>updated.</div><br></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> User will be able to see their Cart </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the Cart View</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208807927-0537f76e-d1fa-484c-be14-e02a09c18c36.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of Cart view<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208808970-a1f699cf-ebc6-4a0f-b161-64f704f2aab2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of the Cart view with different products<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain how the cart is being shown from a code perspective along with the subtotal and total calculations</td></tr>
<tr><td> <em>Response:</em> <div>• All information kept in the cart table is retrieved and shown.</div><div>• Each<br>item's subtotal is determined using the quantity and unit price from the select<br>query.</div><div>• Using the namespace provided by Jinja2, the total is computed by adding<br>each of the subtotals.</div><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a direct link to heroku prod for this file</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/cart">https://is601-mj457-prod-2.herokuapp.com/cart</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> User can update cart quantity </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Show a before and after screenshot of Cart Quantity update</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208809174-7ac585f2-2fd7-4ca9-a9ad-20cb3654f11e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of cart before Quantity update- weather jacket quantity is 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208809461-cd2e725e-56ca-45a8-af5b-f10058ed7bd5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of cart after Quantity update- weather jacket quantity is updated to 5<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Show a before and after screenshot of setting Cart Quantity to 0</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208809461-cd2e725e-56ca-45a8-af5b-f10058ed7bd5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot before  setting Cart Quantity to 0 - weather jacket quantity is<br>5<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208809933-b5100f41-91d2-4452-9ce3-dbd75ba985c0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot After  setting Cart Quantity to 0 - weather jacket got deleted<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Show how a negative quantity is handled</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208810794-a35f2375-5c75-4c9a-9cb2-9259ae88620f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>negative quantity will delete the product from the cart<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain the update process including how a value of 0 and negatives are handled</td></tr>
<tr><td> <em>Response:</em> <div>•The product id is supplied in the post request when the update button<br>is clicked, indicating that an update has occurred.</div><div>• A quantity update is made<br>for each product id.</div><div>• The quantity is examined at each update to see<br>if it is larger than 0. If not, the associated item is removed<br>from the card.</div><br></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Cart Item Removal </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a before and after screenshot of deleting a single item from the Cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208811253-ecfe62be-421b-4fc5-a4d2-6b1c33433a7c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of item before deleting from cart<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208811453-cb30f937-6d3d-4d6d-9b95-0460beaaa9fc.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot After deleting Belt from cart<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a before and after screenshot of clearing the cart</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208811683-ba876119-99c8-4df9-b565-b6f49e68b6ea.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot Before clearing cart<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/113627147/208811683-ba876119-99c8-4df9-b565-b6f49e68b6ea.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot After clearing cart<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how each delete process works</td></tr>
<tr><td> <em>Response:</em> <div>• The logic of the update quantity is likewise followed while deleting each<br>product.</div><div>• When the delete button is clicked, we provide a negative amount value,<br>which removes the associated item from the cart.</div><div>• When the condition is met,<br>I submit the action clear in the post request, which deletes all of<br>that user's products from the database by matching user id.</div><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add related pull request link(s)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Manideep-jagadhabi/IS601-007/pull/18">https://github.com/Manideep-jagadhabi/IS601-007/pull/18</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 10: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe any issues and learnings throughout this milestone</td></tr>
<tr><td> <em>Response:</em> <p>I attempted to incorporate file upload for images when adding new goods, and<br>while it was successful locally, it was unsuccessful on Heroku. I used an<br>alternative method to render photos by including host image URLs. I studied and<br>practiced how to reuse the code effectively for comparable operations like deletion and<br>updating quantity to zero or less.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a link to your herok prod project's login page</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-mj457-prod-2.herokuapp.com/login">https://is601-mj457-prod-2.herokuapp.com/login</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-007-F22/is601-milestone-2-shop-project/grade/mj457" target="_blank">Grading</a></td></tr></table>