
    name = input('what is your name? ')
    print('hey ' + name)
    colour = input('whats your favourite colour? ')
    print(name + ' likes ' + colour)
    weight = input('whats your current weight (lbs): ')
    size = 0.454 * float(weight)
    print(f" your weight in kg: {size}kg")

    # if statement in python
    price = 1000000
    has_good_credit = False
    text = input('so ' + name + ' are you looking to buy a house? ')
    if text.lower() == 'no':
        print('i no blame you na poverty i blame')
    elif text.lower() == 'yes' or 'of course':
        print("that's good here are the down payment")
        if has_good_credit:
            down_payment = 0.1 * price
        else:
            down_payment = 0.2 * price
        print(f"Down payment: ${down_payment}")
    else:
        print('poor man pikin')

    # logical operator
    name1 = input('whats your name? ')
    if len(name1) < 3:
        print("name must be at least 3 characters")
    elif len (name1) > 50:
        print('name must be a maximum of 50 characters')
    else:
        print('name looks good!')
name()
