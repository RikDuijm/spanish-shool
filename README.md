# QueBueno Spanish School Responsive website
In this project I build a new website for QueBueno, a local Spanish school in Breda, the Netherlands. The new owner (my wife) and I are not happy about the existing website we inherited, while it doesn't have the customer in mind, it is very formal, and does not give any impression of the teachers, the teaching materials and the client reviews.

## What does it do and what need does it fulfill?
We wanted to drastically diminish the amount of written information, stock photography and formality on the existing [website](https://www.quebueno.nl/), so that the client can receive an immediate answer to his/her questions, and find in a second the information needed, instead of the main message being diminished by a flood of words. 

The idea is to come across as personal as possible, to give an impression of the teacher and the teaching material, and to provide an immediate answer to questions about the courses (for example price, start dates, location, group size) that an interested person has. Important is also that the visitor is triggered to contact us, asking for a trial lesson, because we see that we have a conversion rate of this lessons of about 90%. In the form, I included the possibility that the visitor already can tell what daypart for the upcoming week he wants the trial lesson planned in. This saves us time, because we do not have to check this by telephone or e-mail to the client.

We've chosen for the yellow and red colors with the Spanish flag in mind, which is well-known in the Netherlands and feel that this evokes a strong and immediate visual recognition among users of the page. Apart from those colors, we only worked with white and a darkish gray, so that the page isn't too juvenile.  


## Functionality and Features
The website is fully responsive and mobile first, on desktop and larger screen sizes there is additional content (in a side bar). However this content is also available on one of the sub-pages, so mobile screen users can also find all the info. The navigation is functional and there is one form. This form is not functional yet, since we didn't learn so far how to implement this. There are links to social media. Facebook and YouTube accounts already exist, I still have to create a Instagram account. 
The website uses audio and video, in which teachers present themselves. Some students are actually quite nervous about contacting us, and about studying Spanish, so we feel that the use of simple speech and a friendly face can help reducing the threshold. 

### Features Left to Implement
It would be of great value to develop a feature that allows the new or existing customer to schedule a time for their first / next lesson. 
It would also be worth considering creating an online payment system for this. Ideally, with an ongoing payment, an invoice should be created automatically and sent digitally to the customer.

In the same way as with the audio and video that we have now used, we can create listening exercises for the client. An extra service to the client would be the creation of online exercises, with for example multiple choice questions and in combination with pieces of grammatical explanation. This should only be accessible to paying customers. We already have these exercises, but we are currently linking to an external website on which we have placed them.

I actually don’t like the presentation of our lesson material. I would prefer to have a pop-up opening with the bigger images instead of opening a blank page, but since this is created with Java I didn’t learn how to do this yet. I would change this asap. 

## Technologies used
I actually don’t like the presentation of our lesson material. I would prefer to have a pop-up opening with the bigger images
- HTML5
- CSS3
- Bootstrap 3.3.7
- Google Fonts
- Font Awesome 4.7.0
- Bash
- Ubuntu
- Git
- YouTube (embedded content)
- Google Maps (embedded content)
- GITHUB
- Google Chrome developer tools
- Cloud 9 

## Testing 
Each page was tested locally and on GITHUB pages using Chrome developer tools, testing its functionality as well as look and feel (in landscape and portrait mode) on 
Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 6/7/8, iPhone 6/7/8, iPhone X, iPad, iPad Pro and responsive desktop. All links were tested, along with the audio control and video player. 

The form is not functional yet. A required attribute is added to the name, telephone and email field.  

Testing in other browsers than Chrome I encountered several issues:
- Firefox: the link in button "Vraag gratis proefles aan" didn't work. Solved this by placing the anchor-tag outside the button instead of inside. 
- Firefox: the audio-file wasn't supported. I've converted the file (m4a) to OGG to make it work. 
- IE / Edge: I had some issues with the whole composition of the website. 
It took me a while to fix this and think it would have been less time consuming to test in the various browsers from the start. Lesson learned!


## Deployment
Website was coded in Cloud 9 IDE, and then uploaded to GITHUB using Ubuntu / Bash script. Once in a GITHUB repositories it was made live using GITHUB Pages. It is deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. The website can be found at: https://rikduijm.github.io/spanish-school/. 

## Credits

### Content
All content on this website was written by me, obviously except for the client testimonials. 

### Media
All photos were taken by me, again except for the photos the clients send me with their testimonials. Audio and video files we're created by me. Presented lesson material by me and my wife. 
The logotype we inherited from the former owner of the Spanish School. Same for the commercial name, that we are planning to change by the way.

