amazon lex
cloud front
route 53
SSL certificate



donate first: https://main.d3aredkst6pbj0.amplifyapp.com/
Git commands:
: git remote rename origin upstream
: git remote add origin URL_TO_GITHUB_REPO
: git push origin master


amazonchatbot:
: Welcome to the Amazon Lex Donation Chatbot! I'm here to assist you in making a donation to your preferred non-profit organization.


Intent Name: DonateIntent

Slot Name: DonationAmount

Description: The amount the user wants to donate.
Slot Type: AMAZON.NUMBER
Prompt: "How much would you like to donate?"
Example Utterances:

"I want to donate {DonationAmount} dollars"
"Can I donate {DonationAmount} dollars?"
"How much do you suggest I donate?"
"What's the minimum donation amount?"
"I can donate {DonationAmount} dollars. Is that okay?"
Slot Name: Name

Description: The name of the user who wants to donate.
Slot Type: AMAZON.US_FIRST_NAME
Prompt: "What's your first name?"
Example Utterances:

"My name is {Name} and I want to donate"
"Can you please take my name {Name} for the donation"
"I'm {Name} and I want to make a donation"
Slot Name: Email

Description: The email address of the user who wants to donate.
Slot Type: AMAZON.EMAIL_ADDRESS
Prompt: "What's your email address?"
Example Utterances:

"My email is {Email} and I want to donate"
"Can you send me the donation receipt to {Email}?"
"What email address should I provide for the donation confirmation?"