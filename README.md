# App Library

Library Reserver App.

# Request Funcionallys

- [] Should be possible sign in;
- [] Should be possible authenticate;
- [] Should be possible save a book
- [] Should be possible save a library
- [] Should be possible get a user profile login;
- [] Should be possible the user search libraries near (until 10 kms)
- [] Should be possible get the number rent books did to the user login
- [] Should be possible the user search books by name
- [] Should be possible the user take a book successfully


## BRs (Business Rule)

- [] The user shouldn't sign in with a duplicate email
- [] The user can't rent three books in same day
- [] The user shouldn't rent a book if owe money
- [] The user has return a book within 7 days
- [] The gym should save only admin


# Request not funcionallys (RNFs)

- [] The password must be crypt
- [] The datas must be persist a PostgreSQL
- [] All list must be page with 20 itens per page
- [] The user must be identify for a JWT