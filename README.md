# Product-Recommender-System
<p>Amazon.com is one of the largest electronic commerce and cloud computing companies. 

<p><b>Just a few Amazon related facts:</b></br>
  They lost $4.8 million in August 2013, when their website went down for 40 mins. They hold the patent on 1-Click buying, and licenses it to Apple. Their Phoenix fulfilment centre is a massive 1.2 million square feet. Amazon relies heavily on a Recommendation engine that reviews customer ratings and purchase history to recommend items and improve sales. 
<p>This is a dataset related to over 2 Million customer reviews and ratings of Beauty related products sold on their website and contains the following features
<li>the unique UserId (Customer Identification),
<li>the product ASIN (Amazon's unique product identification code for each product),
<li>Ratings (ranging from 1-5 based on customer satisfaction) and
<li>the Timestamp of the rating (in UNIX time)

  <p>This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014 and it includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).
    
<p><b> Problem Analysis</b>:
  <li>Amazon uses recommendations as a targeted marketing tool in both email campaigns and on most of its websites pages. Amazon will recommend many products from different categories based on what you are browsing and pull those products in front of you which you are likely to buy. Like the ‘frequently bought together’ option that comes at the bottom of the product page to lure you into buying the combo. This recommendation has one main goal: increase average order value i.e., to up-sell and cross-sell customers by providing product suggestions based on the items in their shopping cart or below products they’re currently looking at on-site.
    
<li>Amazon uses browsing history of a user to always keep those products in the eye of the customer. It uses the ratings and reviews of customers to display the products with a greater average in the recommended and best selling option. Amazon wants to make you buy a package rather than one product. Say you bought a phone, it will then recommend you to buy a case or a screen protector. It will further use the recommendations from the engine to email and keep you engaged with the current trend of the product/ category.
  
  <p><b>Different types of recommendations algorithms used:</b>
  <li>Collaborative filtering
 <li>Content-Based Filtering.
   
  
<p><b>Model performance compariosn and conclusion:</b>
<li>Collaborative filtering model gives recall@5: 0.3847 and recall@10: 0.4759
<li>Content-based filtering model gives recall@5: 0.83814 and recall@10: 0.8630
.
<p>As we can observe that there is better recall value for content-based model than collaborative model.So, we can conclude that content-based model is 
optimal model for product recommendation.
    

  

