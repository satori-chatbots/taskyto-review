# Pizza chatbot interactions in Rasa

## [Interaction 1: Order simple](#interaction-1) ([Taskyto version](pizza.md#interaction-1))

*  :girl:     <span style="color:green">I'd like to order a pizza</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code> 
*  :girl:     <span style="color:green">medium, please</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please tell me what toppings you would like on your medium pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
*  :girl:     <span style="color:green">Ham and bacon, please</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A medium pizza with bacon and ham. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">nothing else</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">Coke and Sprite, please</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your medium pizza order with bacon and ham and coke and sprite is on its way. Have a great time with your pizza and beverages!</code> 


## [Interaction 2: Advance size](#interaction-2) ([Taskyto version](pizza.md#interaction-2))

It misses the chicken topping the first time the user says the list of toppings (this is a defect, it might be fixed with more training phrases).

*  :girl:     <span style="color:green">I'd like to order a medium pizza</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please tell me what toppings you would like on your medium pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
*  :girl:     <span style="color:green">Chicken and ham. Also pepper. And cheese. That's it.</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A medium pizza with cheese, ham and pepper. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">chicken</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A medium pizza with cheese, ham, pepper and chicken. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">That's it</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">Sprite</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your medium pizza order with cheese, ham, pepper and chicken and sprite is on its way. Have a great time with your pizza and beverages!</code> 

## [Interaction 3: Advance toppings and more](#interaction-3) ([Taskyto version](pizza.md#interaction-3))

*  :girl:     <span style="color:green">Hi, I'm Nick Richards, and I'd like a pizza with olives and cheese</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code> 
*  :girl:     <span style="color:green">Small, please</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A small pizza with cheese and olives. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">Please also add pepper. Thanks!</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A small pizza with cheese, olives and pepper. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">That's all</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">Coke and water, please</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your small pizza order with cheese, olives and pepper and coke and water is on its way. Have a great time with your pizza and beverages!</code> 

## [Interaction 4: Advance toppings and drink](#interaction-4) ([Taskyto version](pizza.md#interaction-4))

The chatbot does not get the drink at the beginning of the interaction.

*  :girl:     <span style="color:green">I'd like a small pizza with ham and cheese, and a coke to drink</span> 
*  :computer: <code class="chatbot" style="color:red">I'm sorry it's a little loud in my pizza shop, can you say that again?</code> 
*  :girl:     <span style="color:green">I'd like a small pizza with ham and cheese</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A small pizza with cheese and ham. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">no, that's all</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">a coke to drink</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your small pizza order with cheese and ham and coke is on its way. Have a great time with your pizza and beverages!</code> 


## [Interaction 5: Advance drink](#interaction-5) ([Taskyto version](pizza.md#interaction-5))

*  :girl:     <span style="color:green">I'd like a pizza and a coke, please</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code> 
*  :girl:     <span style="color:green">Small pizza with ham and cheese, please</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your small pizza order with ham and cheese and coke is on its way. Have a great time with your pizza and beverages!</code> 


## [Interaction 6: Going back in the middle of the flow](#interaction-6) ([Taskyto version](pizza.md#interaction-6))

*  :girl:     <span style="color:green">I'm Ann Smith, and I want a medium pizza</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please tell me what toppings you would like on your medium pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
*  :girl:     <span style="color:green">No wait, I think I want a large pizza</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please tell me what toppings you would like on your big pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
*  :girl:     <span style="color:green">No toppings, thanks!</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">Beer, please</span> 
*  :computer: <code class="chatbot" style="color:red">What drink do you want?</code> 
*  :girl:     <span style="color:green">Beer, please</span> 
*  :computer: <code class="chatbot" style="color:red">The drink Beer, please is not available.<br>What drink do you want?</code> 
*  :girl:     <span style="color:green">Yes, then coke and sprite</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your big pizza order with no toppings and coke and sprite is on its way. Have a great time with your pizza and beverages!</code> 


## [Interaction 7: Change toppings](#interaction-7) ([Taskyto version](pizza.md#interaction-7))

It only adds toppings, it does not allow the user to remove them.

*  :girl:     <span style="color:green">Hi, I'm Mick, and I'd like a pizza with olives and cheese</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code> 
*  :girl:     <span style="color:green">Medium please</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A medium pizza with cheese and olives. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">Oh sorry, I don't want olives anymore, but instead ham</span> 
*  :computer: <code class="chatbot" style="color:red">Great choice! A medium pizza with cheese, olives and ham. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
*  :girl:     <span style="color:green">that's all</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
*  :girl:     <span style="color:green">Coke please</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your medium pizza order with cheese, olives and ham and coke is on its way. Have a great time with your pizza and beverages!</code> 

## [Interaction 8: Confirm toppings](#interaction-8) ([Taskyto version](pizza.md#interaction-8))

The chatbot does not understand that the user wants the list of available toppings.

*  :girl:     <span style="color:green">I'd like a pizza and a coke, please</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code> 
*  :girl:     <span style="color:green">A medium one</span> 
*  :computer: <code class="chatbot" style="color:red">What topping do you want?</code> 
*  :girl:     <span style="color:green">Sorry, could you repeat which toppings do you have?</span> 
*  :computer: <code class="chatbot" style="color:red">The topping Sorry, could you repeat which toppings do you have? is not available.
What topping do you want?</code> 
*  :girl:     <span style="color:green">I'd like cheese and pepper. Sorry, not pepper but olives.</span> 
*  :computer: <code class="chatbot" style="color:red">Perfect, your medium pizza order with cheese, pepper and olives and coke is on its way. Have a great time with your pizza and beverages!</code> 


## [Interaction 9: Complex toppings choice](#interaction-9) ([Taskyto version](pizza.md#interaction-9))

The chatbot does not understand that request to list the vegetarian toppings.

*  :girl:     <span style="color:green">I'd like a medium pizza</span> 
*  :computer: <code class="chatbot" style="color:red">Could you please tell me what toppings you would like on your medium pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
*  :girl:     <span style="color:green">Which of the toppings are vegetarian? and vegan?</span> 
*  :computer: <code class="chatbot" style="color:red">We have cheese, ham, pepperoni, bacon, mushrooms, pepper, olives, corn, onion and chicken</code> 
*  :girl:     <span style="color:green">All the vegetarian ones, please</span> 
*  :computer: <code class="chatbot" style="color:red">What topping do you want?</code> 
*  :girl:     <span style="color:green">cheese, mushrooms, pepper, olives and corn</span> 
*  :computer: <code class="chatbot" style="color:red">The topping cheese, mushrooms, pepper, olives is not available.</code> 
*  :girl:     <span style="color:green">What drink do you want?</span> 
*  :computer: <code class="chatbot" style="color:red">Water please</code> 
*  :girl:     <span style="color:green">Perfect, your medium pizza order with corn and water is on its way. Have a great time with your pizza and beverages!</span> 

