# Practice Angular, ASP.NET, SQL Server Project

Continuation of SummitWorks Project

Project Model

Kitchen
KitchenID
Kitchen Name
Email
Password
Kitchen Category
Kitchen Image
NewKitchen

Category
CategoryID
CategoryName

ScheduleEntry
ScheduleID
DayOfWeek
OpenTime
CloseTime

Menu
ItemID
KitchenID
Item Name
Vegan/Non-Vegan
Price
OutOfStock
Discontinued

Shopper
ShopperID
First Name
Last Name
Email
Password

ShopperSecurity
ShopperSecurityID
ShopperID
QuestionID
SecurityAnswer

SecurityQuestion
QuestionID
QuestionBody

Cart
CartID
ShopperID (1 to 1)
TotalItems
TotalPrice

CartEntry
EntryID
CartID
ItemID
ItemQuantity

Order
OrderID
ShopperID
Order Date
Required Date
Expected Date

OrderDetail
DetailID
OrderID
KitchenID
ItemID
Quantity

Order Status
OrderStatusID
OrderID
StatusID
StatusDate

Status
StatusID
StatusName (Outgoing, In The Kitchen, Out the Door, Fulfilled)
