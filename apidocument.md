
#  home page



 https://prphrm.herokuapp.com/maincat

 # append category
https://prphrm.herokuapp.com/categories

#for 2nd Page

# products wrt categoryId
https://prphrm.herokuapp.com/products?categoryId=1

# subcategory Filter products wrt categoryId 
https://prphrm.herokuapp.com/filter/1?subcategoryId=101

# filter cost with respect to category

https://prphrm.herokuapp.com/filter/2?lprice=300&hprice=400

# products wtr filter subcategory lprice hprice filter

https://prphrm.herokuapp.com/filter/2?subcategoryId=202&lprice=300&hprice=400

 # sortby popularity
 https://prphrm.herokuapp.com/filter/2?subcategoryId=201&lprice=100&hprice=400&sratings=-1

# sort byprice
https://prphrm.herokuapp.com/filter/2?subcategoryId=201&lprice=100&hprice=400&=1

# details page

# details of products
https://prphrm.herokuapp.com/details/4

# Orders(GET)
https://prphrm.herokuapp.com/orders
# orders wrt email(GET)
https://prphrm.herokuapp.com/orders?email=sanketpaul7@gmail.com


# place order(Post)
https://prphrm.herokuapp.com/placeorder

{
        "order_id": 1,
        "name": "sanket",
        "email": "sanketpaul7@gmail.com",
        "phone": 7001821411,
        "cost": 234,
        "productId": [
            3,
            5,
            7
        ]
    }
# list of add products items in the cart(Post)
https://prphrm.herokuapp.com/items
{
    "productId":[2,3,6]
}
# update order
https://prphrm.herokuapp.com/updateOrder/1

{
    "bank_name": "udo",
    "date": "20/03/22",
    "status": "success"
}

# Delete Order

https://prphrm.herokuapp.com/deleteOrder/1

