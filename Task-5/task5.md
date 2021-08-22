### Task-5 (10 points):    
- A particular application may require you to keep track of fish and other inhabitants of the ocean. You might have a Shark class, a Tuna class, a Porpoise class. Any behaviours that are common to several classes of animals should be specified in a superclass and inherited by its subclasses. For instance, all animals eat. So you could have an Animal superclass that declares a method for eating. Animal should be an abstract class, since any concrete animal you create will be of a specific animal subclass. There are two kinds of animals, those that move around in the ocean and those that do not. It makes sense to abstract the behaviour of Swimming for a subclass of Animals. So you could have an abstract subclass of the Animal class. Note that the Swimmer class does not have to code the eat method, since Swimmer is abstract. But any concrete class (i.e., a class that you want to create an instance of) that extends Swimmer must implement both eat and swim. Implement the java program for this scenario with the appropriate data members and member functions.  

  ```
   Output:  
   
   The Shark is Swimming  
   The Shark eats Humans  
   The Tuna is Swimming  
   The Tuna eats seaweed  
   The porpoise is Swimming  
   The porpoise eats small fishes  
  ```