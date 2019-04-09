
Preparations

1. Clone this repo.
2. Create branch using this format mm-dd-firstname, e.g. 04-15-allan
3. Download WordPress and put it under your your branch.
4. Install WordPress using MAMP.

WordPress Familiarity

5. Check if there the roles Customer and Subscriber exist. If either not exist, please create.
6. Aside from the admin user that you created, create a user that is a Customer role and another user that is of Subscriber role. Also create a third user with role that is not a Customer and not a Subscriber.
7. Create a page named "Welcome Subscriber".
8. Create a page named "Welcome Customer".

Hooks/Template Familiarity

9. On functions.php on the current theme that is used, make this possible to happen. When a user with role Customer logged in, it will redirect to "Welcome Customer" page. Also if the user with role Subscriber logged in, it will redirect to "Welcome Subscriber" page. Otherwise if a user is not a Customer nor a Subscriber, then it will just go the My Account Page.
