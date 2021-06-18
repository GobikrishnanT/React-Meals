### `Section 1` ---> `navSection with logo`
### `Section 2` ---> `gird of two section --> 1 . commercial 2 . Bill`
### `Section 3` ---> `Section for Food List in grid`


### Css :
### Nav Section :
### `Occupy 12 column`

### Design and construction is over >>
### Now Logic 



### Old state >>

### state 1 {
orderderItem = [

    {Food_Name : "Dosa",
    Per_Food_price : 250,
    Marked_Price : 250,,
    Quantity  : 4}
    ],

totalAmount = 0,
    
}

### New Item >>>
data = {
    Food_Name : "Dosa",
    Per_Food_price : 250,
    Marked_Price : 250,,
    Quantity  : 4
}

This new item Caught at Add Item FUnction >>
### In that I have dispatched a add case in rducer function :
Arguments of reducer function (Old State (come automatically like reduce in js) , action or argument from dispatch)

So we have the old state and new item in our reducer function :
Step 1 > Check Wheather the item is already purchased if it so >
Sol : We have to update the Per_Food_price and Quantity 

Step 1 : If No means  We have to add the item to tha cart :
Sol : 
state.orderItem.push(newItem) :

Again one item is want to add :
newItem = {
    Food_Name : "Pongal",
    Per_Food_price : 100,
    Marked_Price : 100,,
    Quantity  : 1
}

Now state : 
state = {
    orderedItem = [

        {Food_Name : "Dosa",
        Per_Food_price : 250,
        Marked_Price : 250,,
        Quantity  : 4
        },
        {
        Food_Name : "Pongal",
        Per_Food_price : 100,
        Marked_Price : 100,,
        Quantity  : 1
        }
    ]
}



`On Which basis the component is geting re rendered >>>>`

`* Component receives new props.`

`* state is updated.`

`* Context value is updated (if the component listens to context change using useContext).`

`* Parent component re-renders due to any of the above reasons.`


const foodList = [
    {id : "m1",
    Food_name : "Dosa",
    Food_Price : "250",
    Food_Description : "Spr Delicious",
    image : 0},
    {id : "m2",
    Food_name : "Pongal",
    Food_Price : "89",
    Food_Description : "Spr Delicious",
    image : 1},
    {id : "m3",
    Food_name : "Vadai",
    Food_Price : "55",
    Food_Description : "Spr Delicious",
    image : 2},
    {id : "m4",
    Food_name : "Payasam",
    Food_Price : "100",
    Food_Description : "Spr Delicious",
    image : 3},

]"# React-Meals" 
