# AI
1. Import the necessary libraries:
∙ Import the ChatBot class from the ChatterBot library. 
∙ Import the ChatterBotCorpusTrainer class for training the chatbot. ∙ Define any other required variables, like products and response prompts.
2. Create a chatbot instance:
∙ Create a instance with a name (e.g., 'EcommerceBot'). 
ChatBot 
3. Train the chatbot:
∙ Create a ChatterBotCorpusTrainer instance and train the chatbot on the  English language corpus.
4. Define functions and variables:
∙ Define functions to handle product information and user input. ∙ Define product information and response prompts as required.
5. Get user's name:
∙ Prompt the user to enter their name.
6. Start a conversation loop:
∙ Display a welcome message.
7. Within the conversation loop:
∙ Prompt the user for input. 
∙ If the user input is "bye," exit the loop and say goodbye. 
∙ Otherwise, call the function to handle the user's input. 
chatbot_response 
8. Inside the function: 
chatbot_response 
∙ Convert user input to lowercase for case-insensitivity. 
∙ Check if the input contains a greeting. If it does, return a greeting response. ∙ Check if the input is "bye." If it is, return a goodbye response and exit. ∙ If the input contains the word "price," provide a general response about asking  for product prices. 
∙ If none of the above conditions are met, iterate through the products and check  if any product name is mentioned in the input. If found, call the  
get_product_info function and return the product details. 
∙ If none of the above conditions are met, return a generic "I didn't understand"  response.
9. In the function:
get_product_info 
∙ Check if the product name exists in the products dictionary. 
∙ If the product exists, return a formatted response with the product's name, price,  and description. 
∙ If the product doesn't exist, return a "not found" response.
10. Display the chatbot's response to the user's input within the conversation loop.


