# Instructions  

  ## Step 1
  Create an ArrayList of products that store the combination of books, mp3players and TVs

  ## Step 2
  Think about which classes can be made abstract. Go ahead and make them abstract classes !
 
  Note 1: Is it just one class or do we have 2 classes that dont exist in the real world ?

  Note 2: An abstract class can be a parent of another abstract class !

  ## Step 3
  In the Product class, add an abstract method called *usage* that can print message like "This product can be used for __________". 
  Override this method in all applicable child classes.

  ## Step 4
  Create an interface called *Warranty* that contains a method payWarrantyFees. This method must print "You have to pay ____$ for warranty each year on this product".  Warranty must be implemented by Electronics classes. 
  In the sub-classes, override this method. Keep in mind that warranty can be different for MP3 player, TV etc.

  ## Step 5
  All work done above must be tested from the Main.java file
  
  
