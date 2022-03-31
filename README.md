# React Part Time Class Final Project

## Project Links

- [CodeSandbox Link]( - Nothing Yet )

## Project Description

Use this section to describe your final project and perhaps any links to relevant sites that help convey the concept and\or functionality.

 ## Crypto Finacial Tracker
Create a crypto currency finacial tracker app which scans the Binance Smart block chain of a users crypto wallet and pulls in the transaction activity of your metamask wallet address. 
This app aim to help find information to better fill out your taxes and costs associated with token purchases. These fees per transaction associated with  token purchases are tax deductable items in Australia.  


## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.


Wireframes -  https://github.com/shandut/rctr-final-project/blob/main/wireframes%20-%20Project%20idea%202%20-%20Binance%20Smart%20Chain%20Transaction%20Fees%201%20of%202.png

https://github.com/shandut/rctr-final-project/blob/main/wireframes%20-Project%20idea%202%20-%20Binance%20Smart%20Chain%20Transaction%20Fees%202%20of%202.png




### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP Features
- Home page with several sections about my site (Home| About | Finance Tracker | Contact )
- Search Bar for user to input wallet address - Ability for user to search wallet address on the Binance Smart Chain 
- Financal Tracker page that will render transactions info pulled in via an API  
- Ability for user to sort via date, highest to lowest
- Sum up all transaction fees/costs over different time frames(monthly or weekly) (hopefully help with Taxes)

#### PostMVP Features

 - Ability to send report/transaction fees log to Tax Agent via email.
 - Add Auth so other user can used
 - Improve transitions between pages.
 - Data Analysis, month to month comparison of fees charged.
 - Ability for user to export Transaction log to CSV 
 - Maybe also do some sort of analysis if you sold coins for a profit or loss. 
 - Look at Autostaking protocals to see the growth of coins overtime(I am not sure if this data is on the Binance Smart Chain transactions log - will need to confirm.)
 - Click on transaction ID to explore more details about the transaction

## API

If you opted to make use of an API then use this section to include info about the API you have chosen and a code snippet of the data that it returns and is required for your project. 
 Resources 
 - https://bscscan.com/apis 
 - https://docs.bscscan.com/api-endpoints/accounts
 - https://docs.bscscan.com/api-endpoints/tokens
 - https://docs.bscscan.com/api-endpoints/stats

```
{data: {} }
```

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Header | This will render the header include the nav (Home| About | Finance Tracker | Contact ) | 
| HERO | This will render on the Landing Page|
| Content | This will render on the About Us and Contact pages|
| Search | This will render on the Finacial Tracker Page| 
| Finance Grid | This will render on the Finacial Tracker Page|
| Transaction | This will render on the Finance Grid|
| Footer | This will render the header include the nav | 


## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
