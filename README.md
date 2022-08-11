# At-the-pizzeria

Create a Pizza class accepting 1 param ( pizzaId ) \
The class contains the following array with products:
​
```
priceObj = [
            { id: 1, product: "margherita", ingredients: ["tomato", "mozzarella", "basilicum"], price: 7.50 },
            { id: 2, product: "marinara", ingredients: ["tomato", "oregano", "garlic"], price: 5.75 },
            { id: 3, product: "veggy", ingredients: ["eggplants", "peppers", "zucchini", "basilicum"], price: 9.99 }
        ];
```
​
<br>
and the following methods:
<br>
​
- getItem( ) Method - retrieves all details based on product id 
<br>
- print( ) Method - logs following message "you have selected pizza "product". it contains "ingredients" and costs "price" euros"
<br>
- balance( ) Method - logs following message "you paid "amount". your change is "change""       
​
<br>
<br>
<span style="color:lightskyblue">HOW TO RUN </span>
​
const pizza1 = new Pizza( 2 );  <span style="color:#ffae42"> 2 represents the item id from priceObj </span>
​
### RESULT
```
You have selected pizza marinara. 
It contains tomato,oregano,garlic and costs 5.75 euros
```
pizza1.balance( 43 ); 
<br>
​
### RESULT
```
You paid 43 euros. Your change is 37.25
