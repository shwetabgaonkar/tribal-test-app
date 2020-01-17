
#Creted this resposive app as per the .jpg file provided in email

#To launch this app in browser run "npm start" command using git bash or command prompt in src folder (where package.json file located).

#Before running this app run npm install or yarn install command to download node-modules with dependancies mentioned in package.json (node-modules are required in order to run this app)

#Build is available to serve with any static server in side build folder

#Functionalities covered
  * Responsive app(will work fine on any size of device)
  * On product page image rollover zooming is added(as I didn't find the exact image with large size used similar image from google due to which it is not working as expected)
  * on click of "Add to cart"  button product gets added in to the cart and cart icon changes the value in header
  * All the fields like product name, price, discount, cart value etc. are coming through REST api
  * Once you click on "Cart" icon cart page will open through routing and there you will see the list of products in cart
  * If you click on "Delete" that product will get removed from cart and once again the cart icon changes its value in header(it is taking some time to reflect the deleted result 
    due to some issue with mockapi so added a watch item(setInterval) to monitor cart data and getting it cleared on unmount of cart page)

#Used react mockapi (https://www.mockapi.io/projects/5cb46eaabbf7b50014cab994)to develop backend for product and cart
  * product api: http://5cb46eaabbf7b50014cab993.mockapi.io/api/v1/product
  * cart api: http://5cb46eaabbf7b50014cab993.mockapi.io/api/v1/cart
  
# Used REDUX for state management through out the application
  
#Functionality for add to favourite is not covered (it was quite similar as add to cart)