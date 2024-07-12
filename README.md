# rn-assignment7-11160372
 

  # Shopping Cart Application
 This is shopping cart application built with react that uses javaScript . It allows users to view available items,
 select items to cart , remove items from cart and view details of the shopping items

  # Features
 Home Screen: View a list of products.
 Product Details: View product details in a modal.
 Add to Cart: Add products to the cart.
 Cart Screen: View and manage cart items, see the total price.
 Drawer Navigation: Navigate between different sections of the app.

# How It Works

 # State Management
useState: Manages local state (cart items, products, loading status).
useEffect: Fetches data and performs side effects.
  
# Data Storage
AsyncStorage: Saves cart items across sessions.


 # Navigation
React Navigation: Implements stack and drawer navigation.

# Components
Home Screen (HomeScreen.js)
Fetches products from https://fakestoreapi.com/ using axios.
Displays products in a grid with FlatList.
Shows product details in a modal.
Adds products to the cart.
Cart Screen (CartScreen.js)
Retrieves cart items from AsyncStorage.
Displays cart items and total price.
Allows removing items from the cart.
Product Item Component (ProductItem.js)
Displays product image, title, description, and price.
Adds products to the cart.
App Component (App.js)
Sets up navigation using DrawerNavigator and StackNavigator.


# Images
![photo_2024-07-12_23-15-40](https://github.com/user-attachments/assets/a15fc0bc-6868-4fe4-9dbc-05dacca878ae)
![photo_2024-07-12_23-16-31](https://github.com/user-attachments/assets/37ef5231-8265-4bc4-b686-067cd3a3948f)
![photo_2024-07-12_23-28-27](https://github.com/user-attachments/assets/ec1b7696-6132-45cd-b6e4-22ab2c4a0915)
![photo_2024-07-12_23-16-37](https://github.com/user-attachments/assets/f2482d14-ba7e-453f-9ef8-e047fd481453)
![photo_2024-07-12_23-16-47](https://github.com/user-attachments/assets/256b6203-a6eb-42b0-a0a5-6abb440b3578)





