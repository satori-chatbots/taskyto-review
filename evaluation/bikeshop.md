
# Bike shop chatbot interactions in Taskyto


## [Interaction 1: Schedule appointment easy](#interaction-1) ([Rasa version](bikeshop-rasa.md#interaction-1))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for choosing our bike shop for your repair. Could you please provide the date and time you would like to bring in your bike?</code> 
* :girl: <span class="user" style="color:green">26th october 9am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 26/10/2024 at 09:00:00 for a repair.
See you then!</code> 


## [Interaction 2: Schedule appointment saying that the bike is broken](#interaction-2) ([Rasa version](bikeshop-rasa.md#interaction-2))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">Hi</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my bike shop. I'm the owner and I'm happy to help you. What can I do for you?</code> 
* :girl: <span class="user" style="color:green">My bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for letting us know that your bike is broken. To better assist you, could you please provide the date and time you would like to bring your bike in for repair?</code> 
* :girl: <span class="user" style="color:green">tomorrow at 10am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 17/02/2024 at 10:00:00 for a repair.
See you then!</code> 

## [Interaction 3: Schedule appointment asking cost](#interaction-3) ([Rasa version](bikeshop-rasa.md#interaction-3))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">i need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for choosing our bike shop for your repair. To better assist you, could you please provide the date and time you would like to bring in your bike?</code> 
* :girl: <span class="user" style="color:green">before that, which is the cost of the repair?</span> 
* :computer: <code class="chatbot" style="color:red">The cost of the repair can vary depending on the specific issue with your bike. To provide an accurate estimate, we would need to assess your bike in person. Please provide the date and time you would like to bring in your bike for repair, and we will be able to give you a more accurate cost estimate.</code> 
* :girl: <span class="user" style="color:green">ok, then next monday at 5pm</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 31/01/2022 at 17:00:00 for a repair.
See you then!</code> 


## [Interaction 4: Schedule tune-up in a convoluted manner](#interaction-4) ([Rasa version](bikeshop-rasa.md#interaction-4))


* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">My bike needs some adjustments. It is a mountain bike with a Shimano shifter.</span> 
* :computer: <code class="chatbot" style="color:red">It sounds like your bike might need a tune-up. Would you like to schedule an appointment for this service?</code> 
* :girl:     <span style="color:green">Yes, I would like to take the bike to the shop for this</span> 
* :computer: <code class="chatbot" style="color:red">Great! Could you please provide me with the date and time you would like to bring your bike in for the tune-up?</code> 
* :girl:     <span style="color:green">Tomorrow at 12:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 22/02/2024 at 12:00:00 for a tune-up.</code> 

## [Interaction 5: Schedule assuming a repair](#interaction-5) ([Rasa version](bikeshop-rasa.md#interaction-5))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I want to bring my bike to the shop</span> 
* :computer: <code class="chatbot" style="color:red">That's great! Do you need a repair or a tune-up? And could you please tell me the date and time you'd like to bring your bike in?</code> 
* :girl:     <span style="color:green">I need to fix a flat tire. Could I go tomorrow at 10:00?</span> 
* :computer: <code class="chatbot" style="color:red">Save appointment</code> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 22/02/2024 at 10:00:00 for a repair.</code> 
* :computer: <code class="chatbot" style="color:red">See you then!</code> 

## [Interaction 6: Schedule as soon as possible](#interaction-6) ([Rasa version](bikeshop-rasa.md#interaction-6))

In this interaction the day was 21st, and 25th is a Sunday.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I need a repair for my bike</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I can help you with that. Could you please provide me with the date and time you would like to schedule your repair?</code> 
* :girl:     <span style="color:green">as soon as possible, when do you have a spot?</span> 
* Save appointment
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 25/02/2024 at Invalid time for a repair.</code> 
* :computer: <code class="chatbot" style="color:red">See you then!</code> 

## [Interaction 7: Q&A about tires](#interaction-7) ([Rasa version](bikeshop-rasa.md#interaction-7))

The chatbot is partly hallucinating since it is not able to understand that the user may just want a service and it is in "question and answer" mode.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">i need to change the tires of my bike</span> 
* :computer: <code class="chatbot" style="color:red">Sure, I can help you with that. What type of bike do you have?</code> 
* :girl: <span class="user" style="color:green">mountain bike</span> 
* :computer: <code class="chatbot" style="color:red">For a mountain bike, you'll need to choose the appropriate tires based on the terrain you'll be riding on. There are different types of mountain bike tires such as trail tires, cross-country tires, and downhill tires. The prices for new mountain bike tires can vary depending on the brand and quality. It's best to visit a bike shop or check online for specific prices. Is there anything else I can assist you with?</code> 
* :girl: <span class="user" style="color:green">tell me the price of trail tires</span> 
* :computer: <code class="chatbot" style="color:red">I do not know the price of trail tires. However, I can provide information on the prices of a new tire, a tune-up, and a new seat. Additionally, I can offer tips on how to take care of your bike.</code> 
* :girl: <span class="user" style="color:green">just a new tire</span> 
* :computer: <code class="chatbot" style="color:red">The price of a new tire can vary depending on the brand and quality. It's best to visit a bike shop or check online for specific prices. Is there anything else I can assist you with?</code> 
* :girl: <span class="user" style="color:green">which is the price of new tire?</span> 
* :computer: <code class="chatbot" style="color:red">20$</code> 


## [Interaction 8: Q&A conversation](#interaction-8) ([Rasa version](bikeshop-rasa.md#interaction-8))
<!-- 8_qa__wrong_too_harsh -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I have a few questions about bikes</span> 
* :computer: <code class="chatbot" style="color:red">You should clean it regularly, check the tire pressure, and lubricate the chain.</code> 
* :girl: <span class="user" style="color:green">I haven't tell you the question</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry, I haven't received your question yet. Could you please let me know what you would like to ask about bikes?</code> 
* :girl: <span class="user" style="color:green">The thing is that the seat in my bike is broken and I need to replace it</span> 
* :computer: <code class="chatbot" style="color:red">Between 50$ and 100$</code> 

## [Interaction 9: Q&A conversation](#interaction-9) ([Rasa version](bikeshop-rasa.md#interaction-9))
<!-- 9_qa_connect_with_conversation -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">The seat of my bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry to hear that the seat of your bike is broken. We can definitely help you with that. Our bike shop offers seat replacements and repairs. Please bring your bike to our shop and our technicians will take care of it for you.</code> 
* :girl: <span class="user" style="color:green">which is the price?</span> 
* :computer: <code class="chatbot" style="color:red">The price range for a new seat is between $50 and $100.</code> 


## [Interaction 10: Q&A conversation connected to scheduling](#interaction-10) ([Rasa version](bikeshop-rasa.md#interaction-10))
<!-- 10_qa_connect_with_conversation_for_scheduling -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">the seat in my bike is broken</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry to hear that the seat on your bike is broken. We can definitely help you with that. Our bike shop offers a variety of seats for different types of bikes. Please bring your bike to our shop and our team will assist you in finding a suitable replacement seat.</code> 
* :girl: <span class="user" style="color:green">I would like to this tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for choosing our bike shop! Could you please provide the time and type of service you would like?</code> 
* :girl: <span class="user" style="color:green">10am</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 19/02/2024 at 10:00:00 for a repair.
See you then!</code> 


## [Interaction 11: Questions and scheduling](#interaction-11) ([Rasa version](bikeshop-rasa.md#interaction-11))
<!-- 10_question_and_schedule -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">II have a flat tire</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry to hear that you have a flat tire. I can help you with that. Do you need assistance with repairing the tire or do you have any other questions?</code> 
* :girl: <span class="user" style="color:green">first, I want to know the price of a new tire</span> 
* :computer: <code class="chatbot" style="color:red">The price of a new tire is $20.</code> 
* :girl: <span class="user" style="color:green">ok, i agree with this price</span> 
* :computer: <code class="chatbot" style="color:red">The price of a new tire is $20.</code> 
* :girl: <span class="user" style="color:green">that's ok for me</span> 
* :computer: <code class="chatbot" style="color:red">Great! I'm glad the price is acceptable to you. If you would like to proceed with purchasing a new tire, please let me know.</code> 
* :girl: <span class="user" style="color:green">i want to purchase</span> 
* :computer: <code class="chatbot" style="color:red">If you would like to purchase a new tire, please let me know the date and time you would like to come to the shop.</code> 
* :girl: <span class="user" style="color:green">tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for providing the date. Could you please also provide the time and the type of service you need?</code> 
* :girl: <span class="user" style="color:green">10am, change the tire</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have scheduled your appointment for 19/02/2024 at 10:00:00 for a repair.
See you then!</code> 

