# Starbucks-simulation
Starbucks simulation app built applying design pattern using the base code provided by professor.

# CMPE202 Individual Project #

**University Name:**
[http://www.sjsu.edu/](http://www.sjsu.edu/)

**Course:**
Software Systems Engineering

 **Professor:**
 Gopinath Vinodh
 
 **ISA:**
 Akhilesh Anand
 
 **Student Name:**
 Meghana Yoganarasimha

**Disclaimer:**
Actual  solution is not posted in  GitHub Repo visible to the Public. Doing so will violate the "Honor Code" as future students may plagarize my solution.  
 
 **Design Pattern Used :** 
 
* I have added new component in the existing pin screen view called "inValid Component" to show invalid status.The same buffer can reused is required in th efuture.
* Add Card functionality has composite,observermchain of responsibilty implemeted.The View is composed of variuos leaf components like Keypad,spacer,cardcode,card number.Observers are attached to the Keypad as subject,based on the user actions either cardCode or crad number observer is attached.Each entry for the new card details entered by the user are handled by using chain if responsibilty pattern. 
* Singleton pattern is used to store and fetch single card details throughout the app.
* Previuos and next functionality is implemeneted in the Add card screen utilizing existing patterns.
  
  **Composite Pattern:**
      A new component called invalid is added to show the invlaid pin status.
   ![image1](https://user-images.githubusercontent.com/32143377/56940612-5a24b480-6ac4-11e9-8755-f4c1a7c185d2.png)
      
  **Singleton Pattern:**
     Singleton Pattern is used to store and fetch card related information.Class has one instance, and provided a global point of access to it.
 ![image2](https://user-images.githubusercontent.com/32143377/56940648-8d674380-6ac4-11e9-919d-92a5dc980654.png)  
 
  **Composite Pattern:**
       Composite pattern is used to fit all the components in the add card form.Spacer, keypad , cardCode buffer, cardNumber buffer is added as subcomponents to it.
 ![image3](https://user-images.githubusercontent.com/32143377/56940690-d3240c00-6ac4-11e9-884b-5aea309e3e1c.png)  
 
  **Observer Pattern:**
        Observer pattern is used in the add card form to observe the events specific card code and card number events of teh user and update the card details accordingle.Observers are attached and removed from the keypad subject based on th euser actions. 
![image5](https://user-images.githubusercontent.com/32143377/56940763-331ab280-6ac5-11e9-8ee4-93e191414fe2.png)

  **Chain Of Responsibility:**
        Chain of responsibilty design pattern is used to link the next handler of the active observer in the add card screen.
 ![image4](https://user-images.githubusercontent.com/32143377/56940730-01095080-6ac5-11e9-93ac-c69ebaa1bbeb.png)    
**Testoutput:**
![Output](https://user-images.githubusercontent.com/32143377/56940502-b935f980-6ac3-11e9-861d-5a1ed764d8a1.png)
![image6](https://user-images.githubusercontent.com/32143377/56940789-5fceca00-6ac5-11e9-885f-65302fa99978.png)
![imageb](https://user-images.githubusercontent.com/32143377/56940826-9c022a80-6ac5-11e9-8491-50b332b28480.png)
![imagee](https://user-images.githubusercontent.com/32143377/56940844-bf2cda00-6ac5-11e9-8341-d88b4984b76b.png)




        
   
       
        
    
   
     
 
 
 
 

