db.products.insertOne({
    _id:3,
    name:"rubber",
    price:2,
    stock:50,
    reviews:[
        {
            authorname:"sandy",
            rating:5,
            comment:"excellent rubber"
        },
        {
            authorname:"bunny",
            rating:4,
            comment:"good but poor service"
        }
    ]
})