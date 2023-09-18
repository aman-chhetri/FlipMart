<!--Banner-->
![Banner](./screenshots/banner.jpg)

# FlipMart ✨ - A Personalized Product Recommender by Binary Coders </b>
FlipMart aims to embody the functionalities of the well-established and widely used e-commerce platform - FlipMart. This initiative was developed in conjunction with the Flipkart GRID 5.0 program, during which our project centered around addressing the challenge of crafting Personalized Product Recommendations.

## <b> USE-CASE 1 : Personalized Product Recommendations📍 </b><br/>

#### 1. Recommending items based on Past Purchase History 🛒
- Repetition often occurs when shopping for groceries, and a user's historical purchase data plays a pivotal role in delivering valuable suggestions.  
- To generate recommendations based on a user's previous orders, establishing associations between the current item and previously purchased ones is essential.
- The Apriori Algorithm from Association Rule Learning (ARL) is employed to identify these connections among products.
#### 2. Recommending items based on Ratings from Similar Users ⭐
- People residing in the same region often share similar dietary preferences and staple food choices, which is why identifying similar product preferences among them formed the foundation for our exploration of this use case.
- To discover the relevant similarities among users, we employed the Memory-based Collaborative Filtering technique by implementing the nearest neighbors algorithm. This allowed us to identify users who exhibit common trends in their product preferences by analyzing their user rating data.

## <b> USE-CASE 2 : Recipe Integration and Cart Management 🛒 </b><br/>
- Exploring Recipes and Adding Ingredients
- Viewing Recipe Details
- Adding Ingredients to Cart

## Table of Contents ⏬

- [Screenshots](#screenshots)
- [Installation](#installation)
- [Support and Contact](#support-and-contact)

## Screenshots 🖼️

#### Homepage 

![HomePage](./screenshots/Homepage.png)

#### Recommendation Page

![Recommendation](./screenshots/Recommendation.png)

#### Recipify Page

![Recipify](./screenshots/Recipify.png)

#### RecipeInfo Page 

![Recipe Info](./screenshots/RecipeInfo.png)

#### Shopping Cart Page 

![Cart](./screenshots/Cart.png)
## Installation ⚙️
To use this project, follow the steps below:

Initialize git on your terminal.

```bash
git init https://github.com/aman-chhetri/FlipMart.git
```
Clone this repository.

```bash
python app.py
``` 

That's it! Your application is good to go. 

## Support and Contact 📩

Project made by: [Aman Kshetri](https://www.linkedin.com/in/amankshetri/) , [Aman Bhandari](https://www.linkedin.com/in/amankshetri/) and [Raj Sah Rauniyar](https://www.linkedin.com/in/raj-sah-rauniyar/)  - feel free to contact us! 🙂
