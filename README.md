# Lab-1_202001125  
IT314 Software Engineering Lab 1  
   
Question 1: Library Information System  
   
    Functional Requirements: Define features and functions of the project focusing on the user requirements and describing how the project works    
    Non - Functional Requirements: Description of the project and describe the project properties and quality  
     
    Users/Actors of the software:   
        -> Casual readers or non members of the library  
        -> Registered members of the Library  
        -> Library staff  
        -> Librarian or the Administrative user  
       
    Functional Requirements of software:  
        -> Main page of the software has browse books option where anyone can search for a book and in return retrieves information regarding its position in the shelf and its availability  
        -> Main page in the top right corner has a login button which redirects to the login page of the software  
        -> Login page asks to choose between the role through which to login, mainly, User, Staff and Administration and then asked to enter the username and password  
        -> Members page:  
            -> The page can still search for the availability and postion of the book  
            -> But when clicked on the book, it can redirect to bookings page where we can apply in the queue to borrow the book  
            -> On the date of return, if the queue is empty, it shows the option to extend the deadline to return book  
        -> Staff page:  
            -> Can see the present queue for every book by clicking on it  
            -> Approve the top member of the queue and issue it  
            -> Updates the availability of the book when returned  
            -> Approve the extension of book   
        -> Administrative page:   
            -> Option to add and delete available books  
            -> Change postion of the book in the shelf  
            -> Check the individual staff and member pages  
            -> Send notifications to the staff and members regarding anything related to transactions in the library  
            -> Add a member or staff to the library software database   
       
    Non - Functional Requirements of software:  
        -> Usability: Each of the instruction are written clearly with little description boxes near well labelled button name on each page  
        -> Reliability: Unless requiring very drastic change, the software can accomodate changes and is robust over period of time  
        -> Availability: It is available over the institute intranet to all its user  
        -> Scalability: The software database can accomodate all the registered users of the institute and books  
        -> Portability: The application can run on all the platforms  
        -> Security: The software only runs on the institute intranet and uses password protected login pages  
        -> Maintainability: The software is easier to maintain and is cost effective  
      
      
  
Question 2: Hearing Aid Application  
  
    Functional Requirements: Define features and functions of the project focusing on the user requirements and describing how the project works   
    Non - Functional Requirements: Description of the project and describe the project properties and quality  
    Scope: Specify project goals and deliverabilities  
    
    Functional Requirements of software:  
        -> Whenever the app is opened, it hears all the sounds using a sensitive mick and categorise it to different common sounds in everyday life  
        -> The event is declared or written on the screen in big bold letters  
        -> The phone vibrates in place of an event alerting the user and is optional   
        -> Notification can be sent on any wearable devices that can be connected to the phone  
        -> Emergency notification can be sent to contacts describing the sounds and custom message to the user contacts  
    
    Non - Functional Requirements of software:   
        -> Performance: The software workson real time basis with very low latency  
        -> Usability: Each of the instruction are written clearly with little description boxes near well labelled button in big and bright colors for easier readability  
        -> Availability: It is available to all on all the platforms  
        -> Scalability: The software is scalable on increased number of users  
        -> Security: The software is secure and only the user can see the sounds near him unless sent to a contact  
        -> Maintainability: The software is easier to maintain and is cost effective  
      
    Scope:   
        -> To create a real time responding software that alerts the user to sorrounding noises  
        -> Based on feedback, the number of categories of sound can be expanded and updated in all the apps downloaded   
        -> It needs to have low latency to repond to the sorrounding noises  
