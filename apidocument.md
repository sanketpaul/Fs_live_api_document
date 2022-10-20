
#  home page



 https://pharmeasynode.herokuapp.com/maincat

 # append category
https://pharmeasynode.herokuapp.com/categories

#for 2nd Page

# products wrt categoryId
https://pharmeasynode.herokuapp.com/products?categoryId=1

# subcategory Filter products wrt categoryId 
https://pharmeasynode.herokuapp.com/filter/1?subcategoryId=101

# filter cost with respect to category

https://pharmeasynode.herokuapp.com/filter/2?lprice=300&hprice=400

# products wtr filter subcategory lprice hprice filter

https://pharmeasynode.herokuapp.com/filter/2?subcategoryId=202&lprice=300&hprice=400

 # sortby popularity
 https://pharmeasynode.herokuapp.com/filter/2?subcategoryId=201&lprice=100&hprice=400&sratings=-1

# sort byprice
https://pharmeasynode.herokuapp.com/filter/2?subcategoryId=201&lprice=100&hprice=400&=1

# details page

# details of products
https://pharmeasynode.herokuapp.com/details/4

# Orders(GET)
https://pharmeasynode.herokuapp.com/orders
# orders wrt email(GET)
https://pharmeasynode.herokuapp.com/orders?email=sanketpaul7@gmail.com


# place order(Post)
https://pharmeasynode.herokuapp.com/placeorder

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
https://pharmeasynode.herokuapp.com/items
{
    "productId":[2,3,6]
}
# update order
https://pharmeasynode.herokuapp.com/updateOrder/1

{
    "bank_name": "udo",
    "date": "20/03/22",
    "status": "success"
}

# Delete Order

https://pharmeasynode.herokuapp.com/deleteOrder/1

