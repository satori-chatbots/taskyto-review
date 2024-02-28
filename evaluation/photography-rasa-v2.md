# Photography (version 2) chatbot interactions in Rasa


## [Interaction 1: Schedule normal appointment](#interaction-1) ([Taskyto version](photography.md#interaction-1))
<!-- 1_schedule_appointment_normal -->

*  :girl:     <span style="color:green">I need a photo session</span> 
*  :computer: <code class="chatbot" style="color:red">Thank you for contacting us. We will contact you by phone, but we need some additional information. May I please have your full name and phone number. If you have an email address, that would be helpful as well, but it is optional. Also, I need the date you would like to schedule your appointment</code> 
*  :girl:     <span style="color:green">Could you please tell me your name?</span> 
*  :computer: <code class="chatbot" style="color:red">My name is John Doe, my phone number is 555-123456, I do not have email address and I want the appointment tomorrow</code> 
*  :girl:     <span style="color:green">Thanks John Doe! We'll contact you very soon for a session on 28-02-2024</span> 


## [Interaction 2: Schedule appointment advance name and date](#interaction-2) ([Taskyto version](photography.md#interaction-2))
<!-- 2_schedule_appointment_advance_name_date -->

*  :girl:     <span>Hello, my name is Peter Parker, and I need a photo session tomorrow</span> 
*  :computer: <code>Hello Peter Parker. Thank you for contacting us. We will contact you by phone, but we need some additional information. May I please have your phone number. If you have an email address, that would be helpful as well, but it is optional.</code> 
*  :girl:     <span>My phone number is 555-635242, and my email is spider@gmail.com</span> 
*  :computer: <code>Thanks Peter Parker! We'll contact you very soon for a session on 28-02-2024</code> 


## [Interaction 3: Schedule appointment in several steps](#interaction-3) ([Taskyto version](photography.md#interaction-3))
<!-- 3_schedule_appointment_steps -->

*  :girl:     <span style="color:green">I need to photograph my art gallery</span> 
*  :computer: <code class="chatbot" style="color:red">Thank you for contacting us. We will contact you by phone, but we need some additional information. May I please have your full name and phone number. If you have an email address, that would be helpful as well, but it is optional. Also, I need the date you would like to schedule your appointment</code> 
*  :girl:     <span style="color:green">Could you please tell me your name?</span> 
*  :computer: <code class="chatbot" style="color:red">I'm Louise Lane</code> 
*  :girl:     <span style="color:green">Could you share the phone number where we can contact you?</span> 
*  :computer: <code class="chatbot" style="color:red">My phone is 555-123456, I do not have email address</code> 
*  :girl:     <span style="color:green">What day do you want the appointment?</span> 
*  :computer: <code class="chatbot" style="color:red">I'd like the appointment tomorrow</code> 
*  :computer: <code class="chatbot" style="color:red">Thanks Louise Lane! We'll contact you very soon for a session on 28-02-2024</code> 

## [Interaction 4: Schedule appointment with wrong date](#interaction-4) ([Taskyto version](photography.md#interaction-4))
<!-- 4_appointment_wrong_date -->

*  :girl:     <span style="color:green">I need a photo session</span> 
*  :computer: <code class="chatbot" style="color:red">Thank you for contacting us. We will contact you by phone, but we need some additional information. May I please have your full name and phone number. If you have an email address, that would be helpful as well, but it is optional. Also, I need the date you would like to schedule your appointment</code> 
*  :girl:     <span style="color:green">Could you please tell me your name?</span> 
*  :computer: <code class="chatbot" style="color:red">My name is John Doe, my phone number is 555-123456, I do not have email address and I want the appointment yesterday</code> 
*  :girl:     <span style="color:green">I can not schedule an appointment for a past date.</span> 
*  :computer: <code class="chatbot" style="color:red">What day do you want the appointment?</code> 
*  :girl:     <span style="color:green">next Monday</span> 
*  :computer: <code class="chatbot" style="color:red">Thanks John Doe! We'll contact you very soon for a session on 04-03-2024</code> 

## [Interaction 5: Price estimation with all the data](#interaction-5) ([Taskyto version](photography.md#interaction-5))
<!-- 5_price_estimation_all_data -->

*  :girl:     <span style="color:green">I'd like an estimation for a photo session</span> 
*  :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help with that. Could you please provide me with a bit more information? Specifically, I need to know the media you're interested in (photography, video, or 3D rendering), the number of artworks you have, and the type of artworks (picture, sculpture, or ceramic).</code> 
*  :girl:     <span style="color:green">I need to shoot photographs of 3 sculptures</span> 
*  :computer: <code class="chatbot" style="color:red">The price would be around 1500$, but may depend on other factors, like the size of the artworks</code> 

## [Interaction 6: Price estimation of a video session](#interaction-6) ([Taskyto version](photography.md#interaction-6))
<!-- 6_price_estimation_video_session.txt -->

*  :girl:     <span style="color:green">I'd like an estimation for a video session</span> 
*  :computer: <code class="chatbot" style="color:red">Of course, I'd be happy to help with that. Could you please provide me with a bit more information? Specifically, I need to know the number of artworks you have, and the type of artworks (picture, sculpture, or ceramic).</code> 
*  :girl:     <span style="color:green">I have two pictures</span> 
*  :computer: <code class="chatbot" style="color:red">The price would be around 400.0$, but may depend on other factors, like the size of the artworks</code> 



## [Interaction 7: Questions and answers](#interaction-7) ([Taskyto version](photography.md#interaction-7))
<!-- 7_qa.txt -->

*  :girl:     <span style="color:green">Where are you based one, physically?</span> 
*  :computer: <code class="chatbot" style="color:red">The shop is at SoHo, 14 Wooster Street</code> 
*  :girl:     <span style="color:green">Will you be opened tomorrow evening?</span> 
*  :computer: <code class="chatbot" style="color:red">We shoot art on location and on our studio at SoHo. We are open Monday to Friday from 9am to 5pm.</code> 
*  :girl:     <span style="color:green">How do you charge?</span> 
*  :computer: <code class="chatbot" style="color:red">We charge 200$ by hour</code> 
*  :girl:     <span style="color:green">What things do you do? What media is your specialty?</span> 
*  :computer: <code class="chatbot" style="color:red">Mainly on photographs, but also on video, and virtual/3D rendering</code> 


## [Interaction 8: Schedule appointment advancing name](#interaction-8) ([Taskyto version](photography.md#interaction-8))
<!-- 8_schedule_appointment_advance_name2.txt -->

*  :girl:     <span style="color:green">Hello, my name is John Smith</span> 
*  :computer: <code class="chatbot" style="color:red">Welcome to ArtClicks, we are specialized in photographs for art galleries. What can I do for you?</code> 
*  :girl:     <span style="color:green">I want a photo session for tomorrow</span> 
*  :computer: <code class="chatbot" style="color:red">Hello John Smith. Thank you for contacting us. We will contact you by phone, but we need some additional information. May I please have your phone number. If you have an email address, that would be helpful as well, but it is optional.<br>Could you share the phone number where we can contact you?</code> 
*  :girl:     <span style="color:green">My phone number is 555-123456 and I don't have email</span> 
*  :computer: <code class="chatbot" style="color:red">Thanks John Smith! We'll contact you very soon for a session on 29-02-2024</code> 

## [Interaction 9: Schedule with adapted answer](#interaction-9) ([Taskyto version](photography.md#interaction-9))
<!-- 9_schedule_rephrase_in_caller -->

*  :girl:     <span style="color:green">I'm John from The Finest Art Gallery at Soho. I need a photo session for tomorrow. It is urgent. Please, call me at soon as you can at +01 323 232 233, but it is from 10am to 11pm, contact me via Whatsapp.</span> 
*  :computer: <code class="chatbot" style="color:red">Thanks John! We'll contact you very soon for a session on 29-02-2024</code> 


