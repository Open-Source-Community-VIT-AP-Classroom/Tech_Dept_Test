# Main Section

`All the Main Section questions are compulsory`. 

Its okay if you are not able to solve it completely, show us your talent by atleast attempting these questions. You can use any preferred programming language to answer the questions which are not restricted to any other programming language.

### Task-1 (15 Points):
- Write a program in **Python** to decode the secret message in 'secret.txt' file, a small hint: The encoding was done using base64 encoder 😉.

### Task-2 (20 points):

- There can be N pairs of petrol pumps in a range of 80kms of two companies, HP and Indian Oil (IO) arranged alternatively. Now Rearrange them in continuous order, picking up a pair each time. 

  ``` 
   Test Case:  
   For, n=4 (where n is the number of pairs of Hp and Io)    
  
   Input : Hp Io Hp Io Hp Io Hp Io  
   Output Order: Hp Hp Hp Hp Io Io Io Io  
  ```

### Task-3 (20 points):  

- Design Responsive card grid as given shown in image below Using **ReactJS Framework**. Data for cards should be passed **dynamically from useState or .json file**

  ![image](https://user-images.githubusercontent.com/70259716/130324602-fc865880-1be1-450f-8666-485b84f242b0.png)



### Task-4 (25 points):

- Write a program in **Node.js** to Design a simple website that takes a Text Input (search keyword) from the user and with the entered `search keyword` data, the program should send the keyword to google search and your website should scrape the data from the google search site and display only the top 10 data related to the search keyword.

  Hint: You can use web-scraping to achieve this task.

# Bonus Section (Optional)

Note: These questions are easier when compared to the above 4 questions 🤔.

Please attend these questions only if you have completed all the **[Main Section](https://github.com/Open-Source-Community-VIT-AP-Classroom/Tech_Dept_Test/blob/main/Questions.md#main-section)**.

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

### Task-6 (10 points):   
- Define a new exception "ExceptionLineTooLong", that prints out the error message "The String is Too Long". Write a program that reads all user entered string message and throw an exception of type ExceptionLineTooLong in the case where a string is longer than 80 Characters. Also handle all exceptions, that could be thrown by the program.  
  
  ```
   Input: OSC-VITAP OSC-VITAP OSC-VITAP OSC-VITAP OSC-VITAP OSC-VITAP OSC-VITAP OSC-VITAP   
   Output: The String is Too Long
  
   Input: I love OSC
   Output: I love OSC
  ```
