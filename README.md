# Taco Stand

```ruby
taco = Item.new("Taco", 4.50)
# => #<Item:0x007ff01a8c4f80 ... >
taco.name
# => "Taco"
taco.price
# => 4.5

taco.formatted_price
# => "$4.50"

taco.quantity_sold
# => 0

taco.sell
taco.quantity_sold
# => 1
```




