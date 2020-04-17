# Guidelines

Read the scope document in this folder.

# Contributing

1. Fork the repo that you want to contribute to your github user account
2. Make the necessary changes and raise a pull request

‘Fetch’ 
Fetch is the platform for connecting the business who normally supply other (now shut) businesses to the people that need their supplies. Covid-19 has caused significant disruption to major grocery suppliers and with consumers stockpiling, there are empty supermarket shelves across the country. Key workers can’t get access to critical supplies they need to stay healthy, and in turn, keep the country healthy. Before long, it won’t just be key workers that are affected by this disruption. 
Access to groceries – edibles and particularly fresh food – will be critical as we move through this uncertain time. Consumers in isolation or under lockdown will need supplies delivered directly to their houses. Small business are able to deliver and they have the supplies but today they aren’t known by consumers and can’t easily service orders or take payments from them. Fetch aims to resolve this and connect these businesses directly to the consumers who need them.   
Target customers
B2B grocery business that usually deliver to cafes/restaurants/pubs/other shops that are now shut. These businesses don’t have a D2C offering at the moment and this means the platform needs to solve this problem for them including: 
-	Direct to consumer brand presence online 
-	Ability to manage orders and payments directly from consumers
-	Ability to take payments directly from consumers 
-	Ability to manage consumer recourse e.g. refunds/support enquiries 
Location: London, UK but could expand to other locations quickly, depending on supply and demand issues. Focus would be on London in the first instance, expanding to other major cities beyond 
Business model 
-	Set up fee – waived during outbreak (until further notice) 
-	Annual license fee – waived for 1st 6 months 
-	Transactional fee – mark up on costs of taking payment today 
Tech required: 
-	Website for business & for consumers (MVP)
-	Business app for easy order and stock management 
-	Consumer app for search and payment 


MVP scope 
-	Website that allows for: 
o	Businesses to upload stock (with details including pictures, prices etc), manage orders, manage payments. Businesses also need to specify delivery areas and minimum order quantities etc 
o	Consumers to be able to search for grocery availability by their location, likely postcode and understand which suppliers deliver to their area and what they sell. Ideally consumers should be able to search by product (i.e. what they need) within their location but I am not sure how complex this may be to build and would obviously have implications for managing the labelling of stock by suppliers – may be out of scope for an MVP. 
o	Consumers should be able to do guest checkout or store a card on file for repeat purchases 
o	We must be able to manage payments: understand what has been paid to whom and settle back to the appropriate merchant, allow a business to charge a consumer for only what they receive, not what they order (to manage fluctuating stock availability) 
o	We must be able to manage consumer recourse, including support and refunds
o	Consumer dashboard to manage all their deliveries, segmented by category e.g. dairy, fruit & veg, household items, etc. 
Merchant journey (part 1)
1.	A merchant creates a business account on the Fetch website and enters information that helps validate them as a real merchant (type of information TBD but should include business address, registration, bank account details) 
2.	A merchant can then create their profile, with brand/artwork and their name. At this point, they must choose a category or multiple categories that they would like to be seen in the consumer search for. 
3.	A merchant can then begin to upload stock, with photos, pricing and item level details. This can be modified at any point by the merchant and should update live for the consumer on the website
4.	Before the merchant submits changes to the website, they should be able to have a demo view of their profile or the stock item they have created so they can check it before it goes live to shoppers
Shopper journey 
1.	A shopper visits the Fetch website which displays products and categories that are loaded/stored in the website database.
2.	The customer lands on a dashboard that shows the orders they have already created, by category. From this dashboard, they can clearly see all orders due for delivery and when they are due. They can also select any of these orders and book a repeat order (same products on a different date) 
3.	If the customer wants to search for new products, the customer can browse products by categories and ability to deliver to their postcode. 
4.	Customer uses a shopping cart to add items and creates an account with all information saved in the database. It should also allow for guest checkout. Ideally, it should also allow opt in for marketing to be received from the retailer(s) they are purchasing from
5.	Once the customer is in the checkout stage, the website normally goes into secure mode displaying a lock symbol and using an SSL certificate.
6.	While in checkout the website may utilize third-party software or services to provide the customer with delivery options, shipping rates, and expected delivery date.
7.	When the customer enters the credit card number, the information is sent to a payment processor or payment gateway e.g. Stripe
8.	The customer order is now completed and all sensitive information is stored with the payment processor (not with the ecommerce website). An email receipt is generated and sent to the consumer and an order confirmation is displayed on the website 
9.	The customer should receive an email notification/update to their dashboard when the merchant accepts their order
How do we ensure we only charge for what the consumer receives? We will need to ensure the merchant can fulfil the order before payment is taken. Perhaps through pre-authorisation and then charged once the merchant has confirmed they can accept the order and the goods they deliver 
Merchant journey (part 2)
1.	Once the shopper journey is completed, the merchant receives an order summary containing all details required for order fulfilment. This will not contain payment details
2.	The merchant must accept or decline the order and confirm what will be fulfilled and the value of the order e.g. what will be billed
3.	On fulfilment, the merchant can have the payment deposited in their merchant account (a service usually provided by a payment gateway) or transferred to your bank account

Open areas to address 
Supplier vetting:
This is crucial to maintain the integrity of the business and brand as we build it, ultimately gaining trust of consumers to use the platform. There are 3 areas we need to build process and functionality to address:  
1.	Verify that we are onboarding legitimate business/suppliers – look up how this happens on major marketplaces today 
2.	Provide ability for consumer recourse e.g. for poor quality goods or non-delivery – consider how long funds are held for 
3.	Manage refunds 

