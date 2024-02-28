# Photography chatbot interactions in Taskyto


## [Interaction 1: Schedule normal appointment](#interaction-1) ([Rasa version](photography-rasa.md#interaction-1))
<!-- 1_schedule_appointment_normal -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I need a photo session</span> 
* :computer: <code class="chatbot" style="color:red">Great! To schedule your photo session, I will need some additional information. May I please have your full name, phone number, and the date you would like to schedule your appointment? If you have an email address, that would be helpful as well, but it is optional.</code> 
* :girl: <span class="user" style="color:green">My name is John Doe, my phone number is 555-123456, I do not have email address and I want the appointment tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Thanks John Doe! We'll contact you very soon for a session on 15/02/2024. 
</code> 

## [Interaction 2: Schedule appointment advance name and date](#interaction-2) ([Rasa version](photography-rasa.md#interaction-2))
<!-- 2_schedule_appointment_advance_name_date -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">Hello, my name is Peter Parker, and I need a photo session tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Hello Peter Parker, I'm glad to hear you're interested in a photo session. Could you please provide your phone number for us to confirm the appointment? Also, if you wish, you could share your email address with us. This is optional but it would help us to send you updates and special offers.</code> 
* :girl: <span class="user" style="color:green">My phone number is 555-635242, and my email is spider@gmail.com</span> 
* :computer: <code class="chatbot" style="color:red">Thanks Peter Parker! We'll contact you very soon for a session on 15/02/2024.</code> 



## [Interaction 3: Schedule appointment in several steps](#interaction-3) ([Rasa version](photography-rasa.md#interaction-3))
<!-- 3_schedule_appointment_steps -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I need to photograph my art gallery</span> 
* :computer: <code class="chatbot" style="color:red">That sounds like a great project! We can definitely help with that. Would you like to set an appointment for a session, get a price estimate, or do you have any questions about our services?</code> 
* :girl: <span class="user" style="color:green">I'd like to set an appointment</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help you set an appointment. Could you please provide me with your name and phone number? Also, if you could let me know the date you'd like to set the appointment for, that would be great. If you wish, you can also provide your email, but that's entirely optional.</code> 
* :girl: <span class="user" style="color:green">I'm Louise Lane</span> 
* :computer: <code class="chatbot" style="color:red">Nice to meet you, Louise Lane. Could you please provide me with your phone number? Also, could you let me know the date you'd like to set the appointment for? If you wish, you can also provide your email, but that's entirely optional.</code> 
* :girl: <span class="user" style="color:green">My phone is 555-123456, I do not have email address</span> 
* :computer: <code class="chatbot" style="color:red">Thank you for providing your phone number, Louise. The last piece of information I need is the date you'd like to set the appointment for. Could you please provide that?</code> 
* :girl: <span class="user" style="color:green">I'd like the appointment tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Thanks Louise Lane! We'll contact you very soon for a session on 15/02/2024.</code> 


## [Interaction 4: Schedule appointment with wrong date](#interaction-4) ([Rasa version](photography-rasa.md#interaction-4))
<!-- 4_appointment_wrong_date -->

It doesn't validate the date, which is in the past. 

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I need a photo session</span> 
* :computer: <code class="chatbot" style="color:red">That's great! To help you better, could you please provide me with more details about the photo session? Like the type of photos you need, the date you prefer for the session, and your contact information including your name and phone number.</code> 
* :girl: <span class="user" style="color:green">My name is John Doe, my phone number is 555-123456, I do not have email address and I want the appointment yesterday</span> 
* :computer: <code class="chatbot" style="color:red">Thanks John Doe! We'll contact you very soon for a session on 13/02/2024.</code> 

## [Interaction 5: Price estimation with all the data](#interaction-5) ([Rasa version](photography-rasa.md#interaction-5))
<!-- 5_price_estimation_all_data -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I'd like an estimation for a photo session</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help with that. Could you please provide me with a bit more information? Specifically, I need to know the media you're interested in (photography, video, or 3D rendering), the number of artworks you have, and the type of artworks (picture, sculpture, or ceramic).</code> 
* :girl: <span class="user" style="color:green">I need to shoot photographs of 3 sculptures</span> 
* :computer: <code class="chatbot" style="color:red">The cost could be approximately $1500, but it may vary depending on other factors such as the size of the artworks.</code> 

## [Interaction 6: Price estimation of a video session](#interaction-6) ([Rasa version](photography-rasa.md#interaction-6))
<!-- 6_price_estimation_video_session.txt -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I'd like an estimation for a video session</span> 
* :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help with that. Could you please tell me the number of artworks you have and their type? We specialize in pictures, sculptures, and ceramics.</code> 
* :girl: <span class="user" style="color:green">I have two pictures</span> 
* :computer: <code class="chatbot" style="color:red">The cost would be approximately $400, but it could vary based on other factors such as the size of the artworks.</code> 


## [Interaction 7: Questions and answers](#interaction-7) ([Rasa version](photography-rasa.md#interaction-7))
<!-- 7_qa.txt -->


* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">Where are you based one, physically?</span> 
* :computer: <code class="chatbot" style="color:red">The store is located on 14 Wooster Street in SoHo.</code> 
* :girl: <span class="user" style="color:green">Will you be opened tomorrow evening?</span> 
* :computer: <code class="chatbot" style="color:red"> We capture art both on location and in our SoHo studio. Our hours of operation are Monday through Friday, from 9am to 5pm.</code> 
* :girl: <span class="user" style="color:green">How do you charge?</span> 
* :computer: <code class="chatbot" style="color:red">Our hourly rate is $200.</code> 
* :girl: <span class="user" style="color:green">What things do you do? What media is your specialty?</span> 
* :computer: <code class="chatbot" style="color:red">Primarily on photos, but also on videos, and virtual/3D rendering.</code> 



## [Interaction 8: Schedule appointment advancing name](#interaction-8) ([Rasa version](photography-rasa.md#interaction-8))
<!-- 8_schedule_appointment_advance_name2.txt -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">Hello, my name is John Smith</span> 
* :computer: <code class="chatbot" style="color:red">Welcome to ArtClicks, we are specialized in photographs for art galleries. What can I do for you, John Smith?</code> 
* :girl: <span class="user" style="color:green">I want a photo session for tomorrow</span> 
* :computer: <code class="chatbot" style="color:red">Hello John Smith, to finalize your appointment for the photo session tomorrow, could you please provide your phone number? Also, if you wish, you can share your email address with us. This is optional but it would help us to send you updates and offers.</code> 
* :girl: <span class="user" style="color:green">My phone number is 555-123456 and I don't have email</span> 
* :computer: <code class="chatbot" style="color:red">Thanks John Smith! We'll contact you very soon for a session on 16/02/2024.</code>

## [Interaction 9: Schedule with adapted answer](#interaction-9) ([Rasa version](photography-rasa.md#interaction-9))
<!-- 9_schedule_rephrase_in_caller -->

* :computer: <code class="chatbot" style="color:red">Hello</code> 
* :girl: <span class="user" style="color:green">I'm John from The Finest Art Gallery at Soho. I need a photo session for tomorrow. It is urgent. Please, call me at soon as you can at +01 323 232 233, but it is from 10am to 11pm, contact me via Whatsapp.</span> 
* :computer: <code class="chatbot" style="color:red">Thank you, John! We'll get in touch with you as soon as possible to arrange a session for tomorrow. We'll make sure to contact you via Whatsapp between 10am and 11pm.</code> 
