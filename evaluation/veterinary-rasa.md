
# Veterinary chatbot interactions in Rasa

## [Interaction 1: Schedule appointment and ask services](#interaction-1) ([Taskyto version](veterinary.md#interaction-1))

The chatbot does not understand the question about the services offered (this is a defect).

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">Hi</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my veterinary center. I'm the owner and I'm happy to help you. What can I do for you?</code> 
* :girl:     <span style="color:green">I'd like to set an appointment</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help you set an appointment. Could you please provide me with the date, time, and the service you need? The services we offer are Physical examination, Vaccination, Dental health and cleaning, and Lab or diagnostic testing.</code> 
* :girl:     <span style="color:green">Which services do you offer?</span> 
* :computer: <code class="chatbot" style="color:red">We do not open on weekends</code> 
* :girl:     <span style="color:green">I'd like a vaccination for my dog Tobbie, on monday at 16:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have received your request to schedule an appointment for 26-02-2024 at 16:00 for vaccination. See you then!</code> 


## Interaction 2: Schedule appointment in one step

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">Hi, I'm Susan Sarandon</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my veterinary center. I'm the owner and I'm happy to help you. What can I do for you?</code> 
* :girl:     <span style="color:green">I'd like an appointment to vaccinate my dog Jumpy tomorrow at 12:00</span> 
* :computer: <code class="chatbot" style="color:red">Ok, I have received your request to schedule an appointment for 23-02-2024 at 00:00 for vaccination. See you then!</code> 

## Interaction 3: Schedule - Incorrect pet

Fails for the same initial phrase, but with another phrase, it detectes properly that the schedule is for a Sunday.

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">My guinea pig needs to see the vet. Can we schedule an appointment?</span> 
* :computer: <code class="chatbot" style="color:red">f course, I'd be happy to help you set an appointment. Could you please provide me with the date, time, and the service you need? The services we offer are Physical examination, Vaccination, Dental health and cleaning, and Lab or diagnostic testing.</code> 
* :girl:     <span style="color:green">Sunday at 10:00</span> 
* :computer: <code class="chatbot" style="color:red">I can not schedule an appointment for weekends. Select other day to make the appointment</code> 
* :girl:     <span style="color:green">Monday at 10:00</span> 
* :computer: <code class="chatbot" style="color:red">Physical examination</code> 
* :girl:     <span style="color:green">Ok, I have received your request to schedule an appointment for 26-02-2024 at 22:00 for physical examination. See you then!</span> 


## Interaction 4: Questions and answers

Fails to recognise some sentences

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl:     <span style="color:green">What is your schedule at the vet? Can I carry my dwarf elephant on Sunday?</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry, but I did not understand the last sentence, can you say that again?</code> 
* :girl:     <span style="color:green">But then, can I go on Sunday?</span> 
* :computer: <code class="chatbot" style="color:red">We do not open on weekends</code> 
* :girl:     <span style="color:green">And how much is a visit? Does it depend on the kind of animal? or size?</span> 
* :computer: <code class="chatbot" style="color:red">I'm sorry, but I did not understand the last sentence, can you say that again?</code> 
* :girl:     <span style="color:green">Thanks</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to my veterinary center. I'm the owner and I'm happy to help you. What can I do for you?</code> 

