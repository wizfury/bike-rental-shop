~~ DATABASE INFO! ~~

![Database_info](https://github.com/wizfury/bike-rental-shop/assets/68225960/c1508617-67b4-4bda-8444-9510dca9d615)

Database details

~~ TABLE INFO! ~~

![1 Customers_info](https://github.com/wizfury/bike-rental-shop/assets/68225960/50dd4527-9f29-409a-b58b-35a0daa66885)

Customer table info

![2 bikes_info](https://github.com/wizfury/bike-rental-shop/assets/68225960/aee35676-0e86-480f-9fd2-e7aaaf840636)

Bikes table info

![3 rentals_info](https://github.com/wizfury/bike-rental-shop/assets/68225960/25a30678-84c2-4b34-b5c9-0224217a368d)

Rentals table info

~~ TABLE DATA! ~~

![1 Customers_data](https://github.com/wizfury/bike-rental-shop/assets/68225960/11625d67-001a-4409-a5a4-eb7951fd65d4)

Customers Data

![2 bikes_data](https://github.com/wizfury/bike-rental-shop/assets/68225960/46efca9c-ce16-46fc-9819-806588d32190)

Bikes Data

![3 rentals_data](https://github.com/wizfury/bike-rental-shop/assets/68225960/16f9ec4f-06e4-4350-86a5-8f9e029cd086)

Rental Data

~~ WORKING! ~~

https://github.com/wizfury/bike-rental-shop/assets/68225960/e499245f-87b1-4fa7-9ba9-c92fac0d24e5



Here is a simple flow chart:

```mermaid
graph TD;
    START-->RENT;
    START-->RETURN;
    START-->EXIT;
    RENT-->AVAILABLE_BIKES;
    AVAILABLE_BIKES-->PHONE_NUMBER
    PHONE_NUMBER-->FOUND;
    FOUND-->START;
    PHONE_NUMBER-->NOT_FOUND;
    NOT_FOUND-->CREATE_NEW_ID;
    CREATE_NEW_ID-->START;
    RETURN-->PHONE-NUMBER;
    PHONE-NUMBER-->RETURN_RENTAL_ID;
    RETURN_RENTAL_ID-->START;
    
    

```
