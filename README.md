print("====================") 
‎print("     BHM STORE RECEIPT      ") 
‎print ("====================") 
‎name=input("Customer Name: ") 
‎contact=input("Contact No. : ") 
‎address=input ("Address: ") 
‎print("____________________") 
‎
‎product1=input("Product: ") 
‎price1=int(input ("Price: ")) 
‎quantity1=int(input ("Qty: "))  
‎Amount1 = price1 * quantity1
‎print("Amount:", + Amount1) 
‎print ("____________________")
‎product2=input("Product: ") 
‎price2=int(input ("Price: "))  
‎quantity2=int(input ("Qty: "))   
‎Amount2 = price2 * quantity2
‎print("Amount:", + Amount2 ) 
‎print ("____________________")
‎product3=input("Product: ") 
‎price3=int(input ("Price: "))  
‎quantity3=int(input ("Qty: "))   
‎Amount3 = price3 * quantity3
‎print("Amount:", + Amount3) 
‎print("____________________")
‎
‎print(" Product     Price     Qyt     Amount ") 
‎print(product1, "  " ,price1, "  ",quantity1, "  ",  Amount1,) 
‎print(product2, "  " ,price2, "  ",quantity2, "  ",  Amount2,) 
‎print(product3, "  " ,price3, "  ",quantity3, "  ",  Amount3,) 
‎
‎print("____________________") 
‎Subtotal= Amount1 + Amount2 + Amount3
‎print("SUBTOTAL:", + Subtotal)
‎
‎discount=float(Subtotal * 0.10) 
‎print("DISCOUNT(10%):", + discount)
‎
‎print("--------------------")
‎total=Subtotal - discount
‎print("TOTAL AMOUNT:", + total )
‎print("========================")
‎
‎
‎