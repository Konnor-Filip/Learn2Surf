# Course: Authentication
## Module Title: Multifactor Authentication (2/2)
### Module Time: See individual micro-modules
### Assumptions: Students have used passwords before.
### Materials: See individual micro-modules
### Definitions:
* Authentication
* Multi-Factor Authentication
* Factors of Authentication
  * Something you are (Biometrics)
  * Something you have (Token: Smart card/one-time passcode)
  * Something you know (Password/PIN)
  * Somewhere you are (Geo-location)
  * Something you do (Mouse movement/signature)
### Learning Objectives:
* Students will be able to differentiate between the five different factors of authentication. 
* Students are able to describe the types of authentication methods that are most commonly used.
* Students are able to implement the correct level of protection for various types of accounts and devices.
* Students are able to differentiate the positives and negatives of using single-factor authentication vs a multi-factor authentication method.
### Basic Concepts:
Below are a few concepts to help establish your own lessons. Also helpful to create a short 5-10 minute lesson.

1. Identify the three primary and two secondary types of authentication.
* Primary 1: Knowledge/Something you know
  * Examples: Passwords, pin numbers, phone unlock patterns
* Primary 2: Possession/Something you have
  * Examples: Physical card (such as a credit card), one time use password
* Primary 3: Inherent/Something you are
  * Examples: Fingerprint, voice
* Secondary 1: Location
* Secondary 2: Time
2. Identify advantages and disadvantages of using more than one factor when authenticating.
* The primary advantage of multiple factors is that the failure of one factor does not compromise the account.
* The primary disadvantage is the additional time required to access the account. (seconds add up quickly)

#### Class Discovery (Teacher):
What type of groups does your class work well in?
What size of groups can you divide your class into?
What ways do your students learn best?

### Warm-up:
Students will be asked about where they use authentication in their lives. This can include logging in with passwords, using a student ID card at the library, a locker combination, etc. The teacher will have the students discuss how the forms of authentication are different from each other as a lead up to introducing the 5 different forms of authentication. 

## Class Discussion:
### Whole Class Discussion:
**Introduction to multi-factor authentication (Size: Any, Time: 10-20 minutes, Required resources: Provided slides and either access to a computer or a whiteboard)** <br>

**Show**: (Slide-Authentication definition slide) <br>
**Ask**: What does Authentication mean? <br>
**Say**: Authentication is the process or action of verifying the identity of a user or process. <br> 

**Show**: (Slide-Something you know, something you have, something you are) <br>
**Say**: Passwords are just one type of authentication that helps to make sure it is really you on an account. There are many ways that help keep others out of your accounts.

**Show**: (Side-Something you know) <br>
**Say**: The most common type of authentication is something-you-know. Something you know refers to something that you have committed to memory and is something that only you know. An example of something you know is a password, which is the most frequently used something-you-know authentication. <br>
**Ask**: Have you or someone that you know ever used an ATM? What was needed to use it? (Expected responses: a card and a PIN number, hint as needed. An alternative to an ATM includes a checkout at a store) <br>
**Say**: A PIN is another something-you-know type of authentication. Something you know is the most common form of authentication, but is also seen as a weaker form when compared to the other factors. Its strength relies on the complexity and length of the password. PINs are usually less secure than passwords because they are shorter. The card is an example of something-you-have.<br>

**Show**: (Slide-Something you have) <br>
**Say**: The second most common type of authentication is something you have. This is something that is usually physically kept on you. An example of this is the bank cards or credit cards mentioned before. <br>
**Ask**: What other items could be used as a form of something you have authentication? (Expected responses: An ID Card or Mobile Phone App) <br>
**Say**: Something you have can be a variety of different things, which are typically more secure than something you know types of authentication. These can include single use passwords from a phone's apps or text messages and ID badges which can be used to gain access to buildings. While being more secure that passwords because they are physically kept on you, they can be lost or stolen. <br> 

**Show**: (Slide-Something you are) <br>
**Say**: Something you are is a type of authentication that is become more popular. Something you are is often referred to as biometric security. This is something that is unique to you and won't likely change. Fingerprints are unique and are often the most common type of something you are authentication. <br>
**Ask**: Thinking about something that is unique to yourself, what could be used as authentication? <br>
**Say**: There are several things that are unique to you that can be used for biometrics. Fingerprints, eye scanners, facial recognition, and voice recognition are each examples of a biometric authentication and fall under something-you-are. This type of authentication is some of the most secure because of the unique differences in biometrics. However, if the information for your biometrics is ever stolen, they can't be changed. This leads to potentially permanant compromise of security for that system. <br>

**Show**: (Slide-Somewhere you are) <br>
**Say**: Somewhere you are is a type of authentication that uses location for identification purposes. While not commonly noticed, somewhere you are types of authentication are often used to check for activity that is outside of an approved location. An example of this is allowing your phone to unlock automatically while you are home. <br>
**Ask**: Where might somewhere you are authentication be helpful?<br>
**Say**: It may not be the most used or noticeable type of authentication but it is still a helpful form of security. A great example of this is that banks often use location to check to see if money was stolen.

**Show**: (Slide-Something you do) <br>
**Say**: Something you do is a type of authentication that uses routines or patterns that are unique to you for identification. <br>
**Ask**: Is there something in your routine that you consider unique? How could it be used for authentication? <br>
**Say**: This is the least common type of authentication. Technology surrounding it is in the early stages of being developed and maybe become more prominent in the future.  An example of this type of authentication would be detecting a suspicious login at a time you aren't really active on an account. If you normally log into your account between 5p.m. to 10p.m., a login at 3a.m. may be considered suspicious. 

**Show**: (Slide-Multifactor Authentication definition) <br>
**Ask**: What could Multifactor Authentication mean? <br> 
**Say**: The combination of two or more types of authentication to make something more secure. <br>

Have the students break down into individuals or small groups to come up with other examples of authentication they have seen before. Let them work for 3-5 minutes. <br>
Once time is up, have them volunteer examples they have come up with. Record the responses for all to see (whiteboard or computer).<br>
**Discuss**: Go through the responses and identify which ones are single authentication, two-factor authentication, and some ways that additional authentication can be added. <br>

**Example**-Bank card: PIN-know/Card-have <br>
**Example**-Online account: Password-know/Phone-have

## Group Activities
### Small Group:
#### Materials
* Envelopes
* Print outs of cards
* Paper clips to keep envelopes/cards organized

#### Preparation
* Groups of 5 students
* Groups of  5 envelopes with cards inside

#### Goal
Students will roleplay using the "Something they know" and "Something they are" topics that were taught in the lesson. 

#### Activity
Have the students get into groups of five. Give 5 envelopes to each group. Inside the envelopes will be one of three roles for the student to be. Each set of envelopes should have 1 authenticator, 1 gatekeeper, and 3 personnel (personnel can be changed if class size is not divisible by 5).

1. Authenticator (1) - This student will have a card in their envelope with the correct authentication to go through the gate. 
2. Gatekeeper (1) - This student will have a card in their envelope that shows which two types of authentication the personnel need to show to get through the gate. 
3. Personnel (3) - These students will have five different cards in each of their envelopes. These cards will consist of an eye, a fingerprint, a handprint, a password, and a pin number. Each student will have a different variation of these cards (colors/symbols). 

To start the role play, the gatekeeper will say "I need to see ______ and ______ forms of authentication to get through the gate." The blanks are the two types of authentication that were provided in the envelope.

Next, a student with the personnel role will approach the gate and show the two types of authentication requested by the gatekeeper. 

Then the Authenticator will check the color/symbols of the authentication that the personnel showed. If they are correct, the authenticator will say "Authentication Matched". If one does not match, they will say "_____ Matches but ______ does not". Else if neither matches they will say "Authentication Denied"

Based on the Authenticators answer the gatekeeper will either let the personnel through the gate or tell them sorry they are not allowed through.

This process then repeats with the next personnel. 

After the groups have finished, have the students put their cards back in the envelopes and pass them to the next group. This will give each student a chance to play one of the three roles in the game. Repeat for as long as time allows. 

### Wrap-up:
Have students share what they learned through this exercise. Share that authentication can be adjusted in how lenient/strict it is in matching for keeping a location secure. 

### Teacher Reflection:
Do you feel your students have a firm grasp on the types of authentication factors and their usage?
