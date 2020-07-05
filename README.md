# llSPS-INT-2778-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding 
# ADCET Smart Student Care Chatbot
# 1.  Introduction:  
# 1.1 Overview 
  The project is titled as "Intelligent Customer Help Desk with Smart Document Understanding". Here a chatbot is created which unlike other chatbots which answers simple questions and if the particular question is out of the scope then the chatbot typically replies in a manner stating that the question is invalid, intends to answer operational questions by using IBM Watson Discovery service and redirect the customer to the owner's manual that is uploaded in the Watson Discovery sevice. This chatbot leads the customer to the desired section in the owner's manual where the solution for the problem exists instead of redirecting to a customer service.
#  1.2 Purpose 
  The purpose of the project is to save up on the time and money of the owner or manager of the chatbot by reducing the need to connect to a customer care service person by including Smart document Understanding in the chatbot which answers to most of the operational doubts from the organisation's manual thus saving up on time and increasing the efficiency.
# 2. LITERATURE SURVEY 
# 2.1 Existing Problem 
  The typical student care chat bot can answer simple questions, such as admission Procedure and contact details, directions. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.
# 2.2 Proposed solution 
  In this project, there will be another option. If the customer question is about the college Information, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the college manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the college manual to help solve our student’s problems.
# EXPERIMENTAL INVESTIGATIONS
The experimental investigations to get the most appropriate results are as follows
●	Structuring the document/manual using discovery service of IBM. It includes omitting the unwanted text as footer and helping the service understand by laying out the title, subtitles, text, tables among others
●	Trying to parse the file using the webhook to give the most appropriate answer.
●	Modifying and checking which intent works best under which node of the dialog to give appropriate answer.
●	Modifying and checking the node red flow so that the text is fitted well in the ui
●	Modifying and changing the ui according to the need and layout
●	Trying to integrate it with several platforms.
# RESULT
As you can see in the pictures, the user starts off with a normal conversation, the intent of which is recognized by the IBM watson assistant and relevant answer is fetched from the dialog. 
When the user asks any operational query (in my case query about the Annasaheb Dange College of Engineering and Technology) the bot would simply parse the document(ADCET Document) using Watson Discovery and give back the section of the document as a reply to the user.
# APPLICATIONS:
The application of this ADCET Smart Student Care Chatbot is
1.	To answer operational queries
2.	To give real time answers which are usually answered by connecting to a customer care
3.	Helps in knowing the need of the users
# FUTURE SCOPE
The future scope of the project is:
It can be scaled to answer other operational doubts by the college students about the infrastructure, exam and form filling queries
# Video Demonstration
https://youtu.be/avPj8XOAnYE
# Internship Feedback
https://youtu.be/SEKHL4sJRGY
