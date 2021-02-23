# Chatbot Eliza

The chatbot Eliza in this program, is a psychotherapist that was initially developed by Joseph Weizenbaum at MIT, Cambridge. The application made use of pattern matching and substitution methodology with interaction directives written as scripts using MAD-Slip.

This program is an attempt to implement Eliza using Python scripts. The program makes use of word spotting and keyword identification techniques in order to generate meaningful responses to the input. It also transforms statements from the user to questions wherever necessary to convince the user to engage in relevant
conversations. 

The chatbot spots words related to user's greetings, name, request(please), need, words related to user's family, words related to user's emotions(love/hate), definite answers (Yes/No), sorry, thank you etc. It converts statements regarding user's emotions (happy/sad/angry/love/hatred and so on) 
and relationships (father/mother/husband/wife/child and so on) to questions.

Eliza Responses to Input

Eliza (at the beginning of the program) : "Hello! I am Eliza, a psychotherapist. What is your name?"
User : "Hi my name is Amrita" (User can also type just Hi, Hello, not type anything
and just type enter, or wait a few seconds before typing anything - Eliza will give corresponding 
responses to everything!)

Eliza : Hi Amrita. It is nice to meet you. How are you feeling today?
User : I feel depressed. (User could also say "I need help", "I feel/am feeling/am sad/sick/depressed/
/angry/afraid/lonely" and Eliza will respond accordingly.)
Eliza : Talk to me about these feelings (or Can you explain that feeling more?)

User : I miss my mother (User inputs cover a wide scope with all possible immediate family relationships)
Eliza : Tell me about your relationship with your mother.

User : I really don't know what to say.
Eliza : What makes you think that?

User : Well my mother was an amazing person.       
Eliza : Your family and loved ones will be the true well wishers of your life. 

User : You are very sweet Eliza    
Eliza : Well, if you think so!     

User : I feel better now.          
Eliza : That is so good to know!   

User : Thank You for your time.    
Eliza : It is my immense pleasure! 
