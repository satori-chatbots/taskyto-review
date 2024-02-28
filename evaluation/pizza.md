# Pizza chatbot interactions in TaskytoTaskyto version


## [Interaction 1: Order simple](#interaction-1) ([Rasa version](pizza-rasa.md#interaction-1))

 * :computer: <code class="chatbot" style="color:red">Hello</code> 
 * :girl:     <span style="color:green">I'd like to order a pizza</span> 
 * :computer: <code style="color:red">Of course, I'd be happy to assist you with your order. Could you please specify the size of the pizza you'd like? We offer small, medium, and big sizes.</code>
 * :girl:     <span style="color:green">medium, please</span> 
 * :computer:     <code style="color:red">We appreciate your order for a medium pizza!</code> 
 * :computer:     <code style="color:red">Could you please tell me what toppings you would like on your pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
 * :girl:     <span style="color:green">Ham and bacon, please</span> 
 * :computer:     <code style="color:red">Awesome, a pizza with ham and bacon!</code> 
 * :computer:     <code style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
 * :girl:     <span style="color:green">Coke and Sprite, please</span> 
 * :computer:     <code style="color:red">Alright, I've got your order for coke and sprite. Have a great time with your pizza and beverages!</code> 
 

## [Interaction 2: Advance size](#interaction-2) ([Rasa version](pizza-rasa.md#interaction-2))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I'd like to order a medium pizza</span> 
* :computer: <code class="chatbot" style="color:red">I see that you've mentioned a medium pizza. So, the size of the pizza you want to order is medium, correct?</code> 
* :girl:     <span style="color:green">yes</span> 
* :computer: <code class="chatbot" style="color:red">Order pizza medium</code> 
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a medium pizza!</code> 
* :computer: <code class="chatbot" style="color:red">Could you please let me know what toppings you would like on your pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
* :girl:     <span style="color:green">Chicken and ham. Also pepper. And cheese. That's it.</span> 
* :computer: <code class="chatbot" style="color:red">Awesome, a pizza topped with chicken, ham, pepper, and cheese!</code> 
* :computer: <code class="chatbot" style="color:red">Could you please let me know what drink you would like with your pizza? The options are coke, sprite, or water.</code> 
* :girl:     <span style="color:green">Sprite</span> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your order for Sprite. Have a great time with your pizza and beverages!</code> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your order for Sprite. Have a great time with your pizza and beverages!</code> 


## [Interaction 3: Advance toppings and more](#interaction-3) ([Rasa version](pizza-rasa.md#interaction-3))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">Hi, I'm Nick Richards, and I'd like a pizza with olives and cheese</span> 
* :computer: <code class="chatbot" style="color:red">Hi Nick Richards, sure, a pizza with olives and cheese sounds delicious! Could you please specify the size of the pizza? You can choose from small, medium, or big.</code> 
* :girl:     <span style="color:green">Small, please</span> 
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a small pizza!</code> 
* :computer: <code class="chatbot" style="color:red">Great choice, Nick! A small pizza with olives and cheese. Just to confirm, would you like to add any other toppings? We have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken available.</code> 
* :girl:     <span style="color:green">Please also add pepper. Thanks!</span> 
* :computer: <code class="chatbot" style="color:red">Great, a pizza with ['olives', 'cheese', 'pepper']!</code> 
* :computer: <code class="chatbot" style="color:red">Perfect, a small pizza with olives, cheese, and pepper. Now, could you please tell me what you'd like to drink? We have coke, sprite, and water available.</code> 
* :girl:     <span style="color:green">Coke and water, please</span> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your order for coke and water. Have a great time with your pizza and beverages!</code> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your order for coke and water. Have a great time with your pizza and beverages!</code> 

## [Interaction 4: Advance toppings and drink](#interaction-4) ([Rasa version](pizza-rasa.md#interaction-4))

* :computer: <code class="chatbot">Hello</code>
* :girl: <span>I'd like a small pizza with ham and cheese, and a coke to drink</span>
* :computer: <code class="chatbot" style="color:blue">I see that you've already chosen a small pizza. Is there anything else you would like to add to your order?</code>
* :girl: <span style="color:green">no</span>
* :computer: <code class="chatbot">We appreciate your order for a small pizza!</code>
* :computer: <code class="chatbot">I noticed that you've chosen ham and cheese as your toppings. However, we need to confirm if you'd like any additional toppings such as mushrooms, pepper, bacon, pepperoni, olives, corn, or chicken. Could you please specify?</code>
* :girl: <span style="color:green">no, that's all</span>
* :computer: <code class="chatbot">Awesome, a pizza with ham and cheese!</code>
* :computer: <code class="chatbot">I see that you've chosen a coke as your drink. Is that correct?</code>
* :girl: <span style="color:green">Yes!</span>
* :computer: <code class="chatbot" style="color:orange">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code>
* :computer: <code class="chatbot" style="color:orange">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code>


## [Interaction 5: Advance drink](#interaction-5) ([Rasa version](pizza-rasa.md#interaction-5))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I'd like a pizza and a coke, please</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to assist you with that. Could you please specify the size of the pizza you'd like? We have small, medium, and big sizes available.</code> 
* :girl:     <span style="color:green">Small pizza with ham and cheese, please</span> 
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a small pizza!</code> 
* :computer: <code class="chatbot" style="color:red">Thank you for your order. You've chosen ham and cheese as your toppings. Would you like to add any other toppings to your pizza? We also have mushrooms, pepper, bacon, pepperoni, olives, corn, and chicken available.</code> 
* :girl:     <span style="color:green">Also add mushroom and bacon, please</span> 
* :computer: <code class="chatbot" style="color:red">Great, a pizza with ['ham', 'cheese', 'mushrooms', 'bacon']!</code> 
* :computer: <code class="chatbot" style="color:red">Thank you for adding mushroom and bacon to your pizza. I noticed that you mentioned a coke earlier. Just to confirm, would you like a coke as your drink with your pizza?</code> 
* :girl:     <span style="color:green">Yes</span> 
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code> 
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code> 

## [Interaction 6: Going back in the middle of the flow](#interaction-6) ([Rasa version](pizza-rasa.md#interaction-6))

* :computer: <code class="chatbot">Hello</code> 
* :girl:     <span>I'm Ann Smith, and I want a medium pizza</span> 
* :computer: <code class="chatbot">Hi Ann Smith, you mentioned that you want a medium pizza. Just to confirm, is medium the size of the pizza you want?</code> 
* :girl:     <span>yes</span> 
* :computer: <code class="chatbot">Order pizza medium</code> 
* :computer: <code class="chatbot">We appreciate your order for a medium pizza!</code> 
* :computer: <code class="chatbot">Great, Ann Smith. Now, could you please tell me what toppings you would like on your medium pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
* :girl:     <span>No wait, I think I want a large pizza</span> 
* :computer: <code class="chatbot">Order pizza big</code> 
* :computer: <code class="chatbot">Thank you for placing an order for a large pizza!</code> 
* :computer: <code class="chatbot">No problem, Ann Smith. We've updated your order to a large pizza. Now, could you please tell me what toppings you would like on your large pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
* :girl:     <span>No toppings, thanks!</span> 
* :computer: <code class="chatbot">Great, a pizza with []!</code> 
* :computer: <code class="chatbot">Of course, Ann Smith. A large pizza with no toppings. Now, could you please tell me what drink you would like with your pizza? You can choose from coke, sprite, or water.</code> 
* :girl:     <span>Beer, please</span> 
* :computer: <code class="chatbot">I'm sorry, Ann Smith, but we only offer coke, sprite, or water as drink options. Could you please choose from these?</code> 
* :girl:     <span>If you don't have beer, then I want bacon as topping and a coke</span> 
* :computer: <code class="chatbot">Great, a pizza with bacon!</code> 
* :computer: <code class="chatbot">Thank you for your order, Ann Smith. Just to confirm, you would like a large pizza with bacon as a topping and a coke as your drink, correct?</code> 
* :girl:     <span>yes</span> 
* :computer: <code class="chatbot">Perfect, Ann Smith. Your order for a large pizza with bacon and a coke has been confirmed. It will be ready shortly. Thank you for ordering from our pizza shop!</code>

## [Interaction 7: Change toppings](#interaction-7) ([Rasa version](pizza-rasa.md#interaction-7))

In this example the chatbot uses the context data provided by the user to construct a natural output: `Hi Mick, ...`
In addition, the replacement of olives by ham is quite natural.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span style="color:green">Hi, I'm Mick, and I'd like a pizza with olives and cheese</span> 
* :computer: <code class="chatbot" style="color:red">Hi Mick, sure thing! Could you please specify the size of the pizza you'd like? We have small, medium, and big sizes available.</code> 
* :girl: <span style="color:green">Medium please</span> 
* Order pizza medium
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a medium pizza!</code> 
* :computer: <code class="chatbot" style="color:red">Great choice, Mick! You've chosen olives and cheese as toppings. Do you want to add any other toppings to your pizza? We also have mushrooms, pepper, ham, bacon, pepperoni, corn, and chicken.</code> 
* :girl: <span style="color:green">Oh sorry, I don't want olives anymore, but instead ham</span> 
* :computer: <code class="chatbot" style="color:red">Great, a pizza with ['cheese', 'ham']!</code> 
* :computer: <code class="chatbot" style="color:red">No problem, Mick. We'll make your pizza with cheese and ham. Now, could you please tell me what drink you'd like with your pizza? We have coke, sprite, and water available.</code> 
* :girl: <span style="color:green">Coke please</span> 
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code> 
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code> 
* :girl: <span style="color:green">exit</span> 

## [Interaction 8: Confirm toppings](#interaction-8) ([Rasa version](pizza-rasa.md#interaction-8))

* :computer: <code class="chatbot" style="color:red">Hello</code>
* :girl:     <span style="color:green">I'd like a pizza and a coke, please</span>
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to assist you with your order. Could you please specify the size of the pizza you'd like? We have small, medium, and big sizes available.</code>
* :girl:     <span style="color:green">A medium one</span>
* :computer: <code class="chatbot" style="color:red">Order pizza medium</code>
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a medium pizza!</code>
* :computer: <code class="chatbot" style="color:red">Great, a medium pizza. Now, could you please tell me what toppings you would like on your pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code>
* :girl:     <span style="color:green">Sorry, could you repeat which toppings do you have?</span>
* :computer: <code class="chatbot" style="color:red">Of course, no problem. The toppings we have available are: cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, and chicken. Please let me know which ones you'd like on your pizza.</code>
* :girl:     <span style="color:green">I'd like cheese and olives. Sorry, not pepper but olives.</span>
* :computer: <code class="chatbot" style="color:red">Great, a pizza with ['cheese', 'olives']!</code>
* :computer: <code class="chatbot" style="color:red">No problem, we will add cheese and olives to your medium pizza. For the drink, you mentioned a coke earlier. Is that still your choice or would you like to change it?</code>
* :girl:     <span style="color:green">Yes, a coke, please</span>
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code>
* :computer: <code class="chatbot" style="color:red">Alright, your order for coke has been acknowledged. Have a great time with your pizza and beverages!</code>


## [Interaction 9: Complex toppings choice](#interaction-9) ([Rasa version](pizza-rasa.md#interaction-9))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I'd like a medium pizza</span> 
* :computer: <code class="chatbot" style="color:red">I see that you've mentioned a medium pizza. So, I'll take that as your preferred size. Is that correct?</code> 
* :girl:     <span style="color:green">yes</span> 
* :computer: <code class="chatbot" style="color:red">We appreciate your order for a medium pizza!</code> 
* :computer: <code class="chatbot" style="color:red">Great! Now, could you please tell me what toppings you would like on your pizza? You can choose from cheese, mushrooms, pepper, ham, bacon, pepperoni, olives, corn, or chicken.</code> 
* :girl:     <span style="color:green">Which of the toppings are vegetarian? and vegan?</span> 
* :computer: <code class="chatbot" style="color:red">For vegetarian options, you can choose from cheese, mushrooms, pepper, olives, and corn. For vegan options, you can choose from mushrooms, pepper, olives, and corn. Please note that our cheese is not vegan. Could you please tell me what toppings you would like on your pizza?</code> 
* :girl:     <span style="color:green">All the vegetarian ones, please</span> 
* :computer: <code class="chatbot" style="color:red">Great, a pizza with ['cheese', 'mushrooms', 'pepper', 'olives', 'corn']!</code> 
* :computer: <code class="chatbot" style="color:red">Perfect, I've noted down all the vegetarian toppings for your pizza. Now, could you please tell me what drink you would like with your pizza? You can choose from coke, sprite, or water.</code> 
* :girl:     <span style="color:green">Water please</span> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your water order. Have a great time with your pizza and beverages!</code> 
* :computer: <code class="chatbot" style="color:red">Alright, I've got your water order. Have a great time with your pizza and beverages!</code> 
