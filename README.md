# senior-project-2023

      Students often struggle to find cheap products for school at the beginning of the year. There’s websites like Amazon to buy school-related items, but you’re less likely to find students who go to the same school and need the same products as you. Our solution is a website which acts as an online marketplace for students to sell school-related items to other students that go to the same school.
  
      There is a homepage where a user can view the list of items available to purchase. The buyer places an order, and the transaction is confirmed by the seller through the website. From there, they communicate the details of the transaction in person through email. This website is designed to allow students to sell used school-related items in good condition at a low cost.
      
Features:
1. The user adds an entry to their list of items which is displayed on the homepage
2. Users can search for a specific item
3. After finding the item they are looking for, a user confirms the purchase of the item they are looking for
4. The buyer can leave a review for the seller
5. Comments can also be left under each review that is uploaded

      Our functional requirements rely all on the user and what that user wants to do. To use it
though, the user will need to sign up or log in with an existing UTRGV account. Once they can
do either of these, they are on the homepage where they can see all the items available and search for them too. They can also view their user page, their own items up for sale, view pending items they have to accept/decline or their own pending items, view their order history, and log out. If they are logged out, they cannot see any of these options, but they can if they are
logged in.

      For the user page, if they are viewing their own, they can change their profile picture. If
they don’t want to, then they have a default image that everyone else has too. Not only that but if
they are viewing a user page, they can view the items that person has up for sale. Finally, people
are allowed to leave a review if they want to. This applies to everyone, even the user selling the
item, since they might need to clarify or clear up anything that a review left behind.

      For the viewing their own items page, this is where the user can see the items they have
put up and add items as well. Not only that but if they want to remove a listing, they can do that
also. For adding an item, the user will have to fill multiple blanks for the item to be saved into
the database. Not only that but they also must provide pictures so the buyers can see what they
are buying. If the requirements have been met, then it is successfully uploaded, and everyone can
see the listing.

      For viewing pending items, the user can see the orders that someone has made to them.
With this they can accept the order and make the transaction go through or decline and cancel the
order entirely. They can also view their own items they have bought that are pending and cancel
the order if they want to. These options are so the user can have an easier time seeing the orders
to and from them. Order history just views their own history of items they have been able to buy
or not.

      We used a centralized database with a relational model. Javascript is the language that is being used to implement this website. MongoDB is where the database of users, items, orders, and reviews are stored. For Testing we used a combination of different testing libraries: Supertest Jest and Puppeteer.
