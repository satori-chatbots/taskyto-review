
# Veterinary chatbot interactions in Taskyto

## [Interaction 1: Schedule appointment and ask services](#interaction-1) ([Rasa version](veterinary-rasa.md#interaction-1))

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">Hi</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my veterinary center. I'm the owner and I'm happy to help you. What can I do for you?</code> 
* :girl:     <span style="color:green">I'd like to set an appointment</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help you set an appointment. Could you please provide me with the date, time, and the service you need? The services we offer are Physical examination, Vaccination, Dental health and cleaning, and Lab or diagnostic testing.</code> 
* :girl:     <span style="color:green">Which services do you offer?</span> 
* :computer: <code class="chatbot" style="color:red">We offer the following services: Physical examination, Vaccination, Dental health and cleaning, and Lab or diagnostic testing. Which one do you need for your appointment?</code> 
* :girl:     <span style="color:green">I'd like a vaccination for my dog Tobbie, for tomorrow at 16:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have received your request to schedule an appointment for 16/02/2024 at 16:00:00 for Vaccination. See you then!</code> 

## Interaction 2: Schedule appointment in one step

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">Hi, I'm Susan Sarandon</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my veterinary center. I'm the owner and I'm happy to help you. What can I do for you, Susan Sarandon?</code> 
* :girl:     <span style="color:green">I'd like an appointment to vaccinate my dog Jumpy tomorrow at 12:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have received your request to schedule an appointment for 21/02/2024 at 12:00:00 for Vaccination. See you then!</code> 

## Interaction 3: Schedule - Incorrect pet

There are two failures. First, the vet specializes in dogs, cats and birds, so it should not take a guinea pig.
Also, the schedule module is unaware of opening times, so it accepts Sunday as an OK date.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">I have a guinea pig with stomach problems. Can you check it at the vet soon?</span> 
* :computer: <code class="chatbot" style="color:red">Of course, we can arrange a physical examination for your guinea pig. Could you please provide me with the date and time that would be most convenient for you?</code> 
* :girl:     <span style="color:green">Sunday at 10:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have received your request to schedule an appointment for 18/02/2024 at 10:00:00 for Physical examination. See you then!</code> 


## Interaction 4: Questions and answers

In this interaction the chatbot answers take some elements of the user conversation as context, for example when it adds "including Sunday" because (the user mentioned Sunday). 

After the user says "Thanks" the chatbots answers in a polite manner and refering to the current task (asking questions): "You're welcome! If you have any other questions, feel free to ask."

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">What is your schedule at the vet? Can I carry my dwarf elephant on Sunday?</span> 
* :computer: <code class="chatbot" style="color:red">Weekdays from 9am to 6pm</code> 
* :girl:     <span style="color:green">But then, can I go on Sunday?</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry for any confusion, but our veterinary center is open every weekday from 9am to 6pm. We are closed on weekends, including Sunday.</code> 
* :girl:     <span style="color:green">And how much is a visit? Does it depend on the kind of animal? or size?</span> 
* :computer: <code class="chatbot" style="color:red">Between $50 and $60.</code> 
* :girl:     <span style="color:green">Thanks</span> 
* :computer: <code class="chatbot" style="color:red">You're welcome! If you have any other questions, feel free to ask.</code> 


