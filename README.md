Episode one of python series From networkchunk

print("Hello , Welcome to Networkchunk Coffee!!!!!!!!!!!")

name =input("Hello what is your name? \n")

print("Hello, " + name + ",thankyou so much for coming in today.\n \n")

menu = "Black coffee, Latte, Espresso, cappucino"

print( name +  ", what would you like from our menu today? Here is what we are serving today. \n" + menu)

order = input()

price = 8
quantity = input("how many coffees would you like? \n")
total = price * int(quantity)
print("Thankyou. your total is : $ " + str(total))

print ("sounds good "+ name + ", we'll have your " + quantity + " " + order + " ready for you in a moment.")
