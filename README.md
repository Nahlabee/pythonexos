# pythonexos
I am putting some codes.py here just in case I want to use them again!
# Online Python compiler (interpreter) to run Python online.
# Write Python 3 code in this online editor and run it.
def main():
    #ask customer how muc hmoney they have
   wallet=int(input(" How much money do you have ?\n"))
   #create product
   product=50
   answer=int(input(" The product you want to purchase costs " + str(product) + " dollars. Do you still want to buy it ?\n"+
   "1. Yes    2.No \n"))
   #buy and return money
   if answer == 1:
      print("Thanks for buying ! now your credit is " + str(wallet-product) + " DZD")
   #else
   elif answer == 2:
       print("Okay, see you next time !")
   else:
       print("Retry")

  
    
if __name__=='__main__':
    main()
