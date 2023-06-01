# The Retail Store Discounts
### Spring Boot Application using Kotlin
On a retail website, the following discounts apply:
1. If the user is an employee of the store, he gets a 30% discount
2. If the user is an affiliate of the store, he gets a 10% discount
3. If the user has been a customer for over 2 years, he gets a 5% discount.
4. For every $100 on the bill, there would be a $ 5 discount (e.g. for $ 990, you get $ 45
   as a discount).
5. The percentage based discounts do not apply on groceries.
6. A user can get only one of the percentage based discounts on a bill.

## Requirements
- JDK 11
- Kotlin 1.6.21
## Running the application locally
Execute the `main` method in the `BillingApplication` class from your IDE.

### UML Diagram
![Screenshot 2023-06-01 at 15.30.40.png](Screenshot%202023-06-01%20at%2015.30.40.png)

### API Documentation - Postman

      {
      "user":{
      "name":"himanshu",
      "userType":0
      },
      "cartItemList":[
      {"itemName":"soap","itemPrice":200,"category":2},
      {"itemName":"Pant","itemPrice":800,"category":2},
      {"itemName":"Laptop Battery","itemPrice":1000,"category":0}
      ]
      }

