size = input("Jakou chcete velikost pizzy? S, M, nebo L?")

if size == "S" or "s" or "small" or "Small":
    chilli = 20
    pizza = 100
    end = 0
elif size == "M" or "m" or "medium" or "Medium":
    chilli = 30
    pizza = 150
    end = 0
elif size == "L" or "l" or "large" or "Large":
    chilli = 30
    pizza = 200
    end = 0
else:
    print("Bohůžel jsem ti nerozuměl, takže Jeětě naposledy se ptám.")
    size = input("Jakou chcete velikost pizzy? S, M, nebo L?")

    if size == "S" or "s" or "small" or "Small":
        chilli = 20
        pizza = 100
        end = 0
    elif size == "M" or "m" or "medium" or "Medium":
        chilli = 30
        pizza = 150
        end = 0
    elif size == "L" or "l" or "large" or "Large":
        chilli = 30
        pizza = 200
        end = 0
    else:
        print("Bohužel jsem vám opět nerozuuměl, takže se mějte hesky, jelikož tu mám i jiné zákazníky")
        end = 1

if end == 0:
    chilli_yes_no = input("Chcete Feferonky? A nebo N")

    if chilli_yes_no == "Ano" or "A" or "a" or "ano":
        price = chilli + pizza
        end = 0
    elif chilli_yes_no == "Ne" or "N" or "n" or "ne":
        price = pizza
        end = 0
    else:
        print("Bohůžel jsem ti nerozuměl, takže Jeětě naposledy se ptám.")
        chilli_yes_no = input("Chcete Feferonky? A nebo N")

        if chilli_yes_no == "Ano" or "A" or "a" or "ano":
            price = chilli + pizza
            end = 0
        elif chilli_yes_no == "Ne" or "N" or "n" or "ne":
            price = pizza
            end = 0
        else:
            print("Bohužel jsem vám opět nerozuuměl  takže se mějte hesky mám tu i jiné zákazníky")
            end = 1


    if end == 0:
        cheese_yes_no = input("Chcete sýr navíc? A nebo N")

        if cheese_yes_no == "A" or "a" or "Ano" or "ano":
            price = price + 20
            end = 0
        elif cheese_yes_no == "N" or "n" or "Ne" or "ne":
            end = 0
        else:
            print("Bohůžel jsem ti nerozuměl, takže Jeětě naposledy se ptám.")
            cheese_yes_no = input("Chcete sýr navíc? A nebo N")

            if cheese_yes_no == "A" or "a" or "Ano" or "ano":
                price = price + 20
                end = 0
            elif cheese_yes_no == "N" or "n" or "Ne" or "ne":
                end = 0
            else:
                print("Bohužel jsem vám opět nerozuuměl  takže se mějte hesky mám tu i jiné zákazníky")
                end = 1



if end == 1:
    print("Nashledanou. Mějte hezký den!!!")
elif end == 0:
    print(f"Děkujeme za obědnání pizzy.\nCena pizzy je {price}. Uhraďte je prosím, až u nás na prodejně při vyzvednutí. ")
