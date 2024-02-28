
# Bike shop chatbot interactions in Rasa


## [Interaction 1: Schedule appointment easy](#interaction-2) ([Taskyto version](bikeshop-rasa.md#interaction-2))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">26th october 9am</span> 
* :computer: <code class="chatbot" style="color:red">The shop is closed on weekend. Please select other day to make the appointment</code> 
* :girl: <span class="user" style="color:green">29th october</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 29-10-2024 at 09:00 for repair. See you then.</code> 


## [Interaction 2: Schedule appointment saying that the bike is broken](#interaction-2) ([Taskyto version](bikeshop.md#interaction-2))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">Hi</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my bike shop. I'm the owner and I'm happy to help you. What can I do for you?</code> 
* :girl: <span class="user" style="color:green">My bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">tomorrow at 10am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 10:00 for repair. See you then.</code> 


## [Interaction 3: Schedule appointment asking cost](#interaction-3) ([Taskyto version](bikeshop.md#interaction-3))

The chatbot does not understand the question about the price of a repair.


* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">i need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">before that, which is the cost of the repair?</span> 
* :computer: <code class="chatbot" style="color:red">I can not understand the date, please try again. What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">ok, then next monday at 5pm</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 04-03-2024 at 17:00 for repair. See you then.</code> 


## [Interaction 4: Schedule tune-up in a convoluted manner](#interaction-4) ([Taskyto version](bikeshop.md#interaction-4))


* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">My bike needs some adjustments. It is a mountain bike with a Shimano shifter.</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for tune-up your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?</code> 
* :girl:     <span style="color:green">Tomorrow at 12:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 00:00 for tune-up. See you then.</code> 


## [Interaction 5: Schedule assuming a repair](#interaction-5) ([Taskyto version](bikeshop.md#interaction-5))

The chatbot has a defect because it changes 10:00 to 22:00.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I want to bring my bike to the shop</span> 
* :computer: <code class="chatbot" style="color:red">TThank you for contact us. I can schedule you an appointment in our bike shop for tune-up or repair your bike. And could you please tell me the date and time you'd like to bring your bike in? What day do you want to come in?</code> 
* :girl:     <span style="color:green">I need to fix a flat tire. Could I go tomorrow at 10:00?</span> 
* :computer: <code class="chatbot" style="color:red">The shop is close at 22:00. Our opening hours are from 9am to 5:30pm. Please select a time between that. What time works for you?</code> 
* :girl:     <span style="color:green">10am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 10:00 for repair. See you then.</code> 


## [Interaction 6: Schedule as soon as possible](#interaction-6) ([Taskyto version](bikeshop.md#interaction-6))

The chatbot does not understand "as soon as possible".

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?</code> 
* :girl:     <span style="color:green">as soon as possible, when do you have a spot?</span> 
* Save appointment
* :computer: <code class="chatbot" style="color:red">I can not understand the date, please try again
What day do you want to come in?</code> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 09:00 for repair. See you then</code> 

## [Interaction 7: Q&A about tires](#interaction-7) ([Taskyto version](bikeshop.md#interaction-7))

The chatbot does not understand the question about the price of the tires.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">i need to change the tires of my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for tune-up or repair your bike. And could you please tell me the date and time you'd like to bring your bike in?</code> 
* :girl: <span class="user" style="color:green">I have a mountain bike, tell me the price of new trail tires. How much the overall service will be?</span> 
* :computer: <code class="chatbot" style="color:red">I can not understand the date, please try again What day do you want to come in?
</code> 


## [Interaction 8: Q&A conversation](#interaction-8) ([Taskyto version](bikeshop.md#interaction-8))
<!-- 8_qa__wrong_too_harsh -->

The chatbot does not understand the first interaction which introduces the goal of the user.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I have a few questions about bikes</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for tune-up or repair your bike. And could you please tell me the date and time you'd like to bring your bike in?
What day do you want to come in?</code>



## [Interaction 9: Q&A conversation](#interaction-9) ([Taskyto version](bikeshop.md#interaction-9))
<!-- 9_qa_connect_with_conversation -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">The seat of my bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike? What day do you want to come in?
</code> 

## [Interaction 10: Q&A conversation connected to scheduling](#interaction-10) ([Taskyto version](bikeshop.md#interaction-10))
<!-- 10_qa_connect_with_conversation_for_scheduling -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">the seat in my bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for repair your bike. Could you please provide the date and time you would like to bring in your bike?
What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">I would like to this tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">What time works for you?</code> 
* :girl: <span class="user" style="color:green">10am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 10:00 for repair. See you then.</code> 



## [Interaction 11: Questions and scheduling](#interaction-11) ([Taskyto version](bikeshop.md#interaction-11))
<!-- 10_question_and_schedule -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">II have a flat tire</span> 
* :computer: <code class="chatbot" style="color:red">The cost of a new tire for your bike is 20$</code> 
* :girl: <span class="user" style="color:green">i want to purchase</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for contact us. I can schedule you an appointment in our bike shop for tune-up or repair your bike. And could you please tell me the date and time you'd like to bring your bike in? What day do you want to come in?</code> 
* :girl: <span class="user" style="color:green">tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">TWhat time works for you?</code> 
* :girl: <span class="user" style="color:green">10am, change the tire</span> 
* :computer: <code class="chatbot" style="color:red">We can service or repair your bike.  Which one would you like?
</code> 
* :girl: <span class="user" style="color:green">repair</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 27-02-2024 at 10:00 for repair. See you then.</code> 

