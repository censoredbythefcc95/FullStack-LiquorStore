# BOOZEBROS - a Full-Stack MERN (Mongo, Express, React, Node) Application

## Project Links

- [Frontend GitHub Repo Link](https://github.com/censoredbythefcc95/FullStack-LiquorStore)
- [Live Project Link](https://boozebrosapp.herokuapp.com)


## Project Description

BOOZEBROS is a full-stack web application created for a fictional NYC liquor store named BOOZEBROS. This is a simple MERN application that serves a a basic e-commerce solution for customers that wish to purchase alcohol and other products. The first version of BOOZEBROS was my Capstone Project for General Assembly's Software Engineering Immersive - Remote cohort (SEIR). 

Customers will be able to:
- View current inventory of beer, liquor, wine and other items for sale. 
- See how much product is in stock
- Use the online order system to place an order for delivery.
- "Pay" for their items online using integrated PayPal API.

## Project Completion status

| Project Phase | Status/Notes | 
| --- | :---: |  
| Project Approval | Complete | 
| Planning Architecture | Complete | 
| React server set-up| Complete | 
| Express server set-up | Complete |
| Schema planning and creation | Complete |
| Express route configuration | In Progress |
| Backend endpoint route configuration | In Progress |
| React front-end primary set-up | In Progress  |
| Fetching API call into React components | In Progress |
| Functionality testing | In Progress |
| CSS Styling | Not started. |

## Architecture 

- Coming Soon.


## API

I will create my own API on Express for the alcohol inventory. I will implement Stripe API with Firebase(user authentication) for the checkout page.(POSTMVP)


```
{
    _id: '2',
    name: 'Black Label',
    description: 'The expensive stuff. Time to get lit',
    brand: 'Johnnie Walker',
    category: 'Liquor',
    price: 149.99,
    countInStock: 15,
    rating: 5,
    numReviews: 2,
    image: '/images/blacklabel.jpg',
},
```


## Wireframes

- Coming Soon.

#### MVP - Neccesary tasks to make application functional.

- Be a working, interactive, full-stack application. 
- Include data from back-end API 
- Have at least 5 separate components, using a readable file structure. 
- Built with new technologies (Redux, PayPal API, Morgan, Concurrently)
- Built mobile first. 
- Implement responsive design using Flexbox and Bootstrap. 
- State Management up and running using Redux for React, and React hooks like useEffect, useDispatch, useState. 
- Be deployed via Heroku.

#### PostMVP EXAMPLE

- Styling based on Material UI to make the application more aesthetciailly pleasing, 
- Add additonal functionality such as coupon codes to lower price of item, as well as free shipping.
- Add Javascript animations to the application. 
- Implement status system for customers to see status of their order. Currently, the admin can set the order between "Delivered" and "Not Delivered." However, this should be "Order received", "Order is being prepared", "Order is on the way", and "Order has been delivered."

## Components
This project has components seperated into two categories, Components and Screens. 

| Screen| Description | 
| --- | :---: |  
| App | Heart of the application.| 
| Head | This will hold the Navigation Bar. | 
| Rating | Component that houses rating function and displays in the Drink component.  | 
| Drink | Component card displaying drink, price, rating. |
| HomeScreen | Home Screen. Will hold the landing page. |
| ProductScreen | Shows current inventory of alcohol. |
| Footer | Contains footer text with creator.|

CartScreen
HomeScreen
LoginScreen
OrderListScreen
OrderScreen
PaymentScreen
PlaceOrderScreen
ProductEditScreen
ProductListScreen
ProductScreen
ProfileScreen
RegisterScreen
ShippingScreen
UserEditScreen
User List Screen

CheckoutSteps
Footer
FormContainer
Header
Loader
Message
Meta
Paginate
Product
ProductCarousel
Rating
SearchBox 












| Component | Priority | Estimated Time | Time Invested |
| --- | :---: |  :---: | :---: | 
| Initializing framework/app | H | 1 hr | 1 hr | 
| Netlify Deploy | H | 1 hr | 1 hr |
| Heroku Deploy | H | 1 hr |  0 hrs | 
| Build API | H | 3 hrs | 4 hrs | 
| Express Routes | H | 3 hrs| 4 hrs | 
| Building Components | H | 8hrs| 8hrs | 
| React routes | H | 6hrs | 4hrs | 
| Rendering data pull from API | H | 2 hrs | 2 hrs |
| CSS Styling | M | 25 hrs | 1hrs | 
| Double-checking State and Routes | H | 2 hrs | hrs |
| Total | H | 51hrs | 25hrs |


## Additional Technologies

- React
- Stripe API
- Firebase for User Authentication
- GraphQL

## Final notes 

I still need to determine my final component architecture. It is still unclear. Research on best architecture in progress.

- Rethink timing for MVP / PostMVP
- Figure out architecture
- Make sure documentation is really in place before starting(still unclear)
- Research GH and other sites for design. 

## Roadblocks / Questions

- Is it still a good avenue to go down User Authentication?
- Am I overcomplicating my code?
- Am I following good practice with React Component builds?
- useEffect hook when assigning state? 