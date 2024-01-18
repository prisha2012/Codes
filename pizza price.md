size=input()
toppings=int(input())

def price(size,toppings):
    base_price={"small":10,"medium":15,"large":20}
    base=base_price[size]
    topp=toppings*2
    cost=base+topp
    print(f"{cost}")
price(size,toppings)
