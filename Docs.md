DOCUMENT COMPARISON

- Document Comparison tool: Tool that checks for the similarities and differences between two documents uploaded to the tool 

- The purpose: 
Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user uploads two documents and asks for similarities and differences between the documents dependent on the discretion of the user 	-The AI tool responds on time and gives the options of choosing from “Show me the similarities” and “Show me the differences”

-Creates a table that shows the desired result with very low latency and the option to export those answers as a .csv file	- Exactly 2 documents with at most 10MB as the size for it for each document 
- Check if the options are present.
- Check if the output is exportable/shows in the .csv file.



SAY IT

- SAY IT tool: A tool that converts written text into an audio speech file 
- The purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user types in any combination of words as a request to the AI tool to create the audio file 	-The AI tool responds on time and provides the audio file for the sentence provided  

- The longer the text, the longer the wait although it has a quick response time and low latency regardless.
	- Any combination of text from any language 




SAY IT PLUS

- SAY IT PLUS tool: A tool that converts written text into an audio speech file
- The purpose:  

Key developer(s): Laura
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user types in any combination of words as a request to the AI tool to create the audio file 	-The AI tool responds on time and provides the audio file for the sentence provided  

- The AI tool initially gives the opening text with three options and suggestions for the usage of this tool such as a voice over for presentations

- It provides different voices for the tool: Andrew, Ava, Brian and Emma

-The three options provided are “Help with voice selection”, “Speak text I want to provide” and, “generate text, like stories, poems and jokes”

- It also gives the option to shorten, summarize and reformat the text for a cleaner narration.

-It gives the option to generate  stories, poems and jokes. Within that it gives the user to choose the genre of the poem or story, how long it should be and the style 


	- Any combination of text from any language

- Ensure that it can give the speech in each of the four voices 

- Ensure that it can generate stories, poems and jokes that can be narrated by the AI voice agent.

-




SUMMARIZATION SKILL


- Summarization Skill tool: A tool that effectively summarizes a pdf file or plain text. 
-The purpose:  

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user gives a long plain text or a pdf to the AI tool to summarize it and break it down into shorter and more concise points.	-It begins with a text asking to drop the text or the PDF for summarization.

- It summarizes the document in a very short and concise manner

- It has a very fast response time and low latency 	- It can take only one pdf file that has a maximum of 10 MB 
- Ensure that the summary is related and contains the core information as the required text.





EMAIL COMPOSER SKILL
 Email Composer tool: This is a tool used to compose emails 
The purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The User asks to compose an email	-It begins with a text asking if you are ready to write an email before presenting two options, “Reply to an email” and “compose a new email”

- It provides the user with the opportunity to give as much context to the email before getting the response 

-The reply to an email option also comes out well as it can be given more context before receiving a response.
The tone, subject and recipient can be added to make the email better suited.

-The latency of the response was extremely low and was given a response in a very short amount of time 	- The testing should ensure that the email generated follows the required prompts and follows the required structure of a standard email

-If it responds in the correct language 

-How well it comes out with contradictory constraints such as “formal but funny” 










ADHESIVES TECHNICAL Q&A
 Adhesives Technical Q&A: This AI tool searches Henkel adhesives technical data sheets to return concise, fact-based answers with source citations.

The Purpose

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user gives a question about an adhesive that Henkel is developing/developed	- It begins with the AI tool asking about product specifications like the viscosity, curing mechanism, operating temperature, or handling instructions.

-It then has suggested prompts and when clicked on each prompt it gives a response with a link to the source of the answer

- It has low latency and the responses to the prompts are given in a swift manner.	-The verification of the links and if they work 

- Verification if the response given to the prompt is still valid after improvements in technology 


		







AI VOICE ASSISTANT
AI Voice Assistant: This AI tool enables the user to have real-time conversation with an AI assistant capable of carrying out instructions through voice commands

The Purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user gives instructions to the chatbot using their voice	- It begins with the AI tool querying “Hello!, How can I help you today?”

- The User then responds using their voice 
- The AI Agent then begins to respond to the prompt spoken by giving a response typically in relation 
- If the agent is not the best suited to the request, it can communicate with other agents and delegate the task towards them before retrieving the response
-  The response time is quick, and the latency is low for the testing 	- If it correctly captures the voice commands accurately
-If it is successful in A2A communication
- If the conversation freezes or not
- If the agent continues conversations after an interruption.
- if the agent is successful in giving an accurate response to a prompt/command






PACKSHOT CHECKING TOOL
Packshot Checking Tool: Users upload a CSV with image links; the system checks compliance and generates an Excel report.

The Purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user uploads a CSV file with image links to check for compliance and to get a generated Excel report 	-	It sends a message requesting for the .csv file to be sent 
-	It then analyses the file sent and the image links picture by picture 
-	The more pictures uploaded the longer it takes although the analysis time taken is very short.
-	It then at the end, creates an excel spreadsheet with the analysis in it 	-	It accepts 1 .csv file with a maximum of 10MB in size 
-	Ensure that the Excel file generated at the end contains the analysis of the file.
-	The analysis in the file is accurate, and the requirements are duly checked.
-	Enabling the user to override data is critical, possible through the Excel download





GENERAL CONVERSATION TOOL
General Conversation Tool: This AI tool enables the user to have real-time conversation with an AI assistant capable of carrying out instructions.
The Purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
The user gives instructions to the AI assistant through commands and prompts  	- It begins with the AI tool querying “Hello! How can I help you today?”

- The User then responds by sending prompts  

- The AI Agent then begins to respond to the prompt given by giving a response to the prompt in the specific tone and language specified.
- If the agent is not the best suited to the request, it can communicate with other agents and delegate the task towards them before retrieving the response
-  The response time is quick, and the latency is low for the testing	-If it is successful in A2A communication
- If the conversation freezes or not
- If the agent continues conversations after an interruption.
- if the agent is successful in giving an accurate response to a prompt/command


- If it can recognize the intent within the command/prompt



RESEARCH SKILL TOOL
Research Skill Tool: This AI tool enables the user to generate an academic-grade research paper using a singular prompt that contains the topic and the scope of the research paper.

The purpose:

Key developer(s): 
 
Trigger 
(what the user asks for)	Expected Behavior 
(what the response is, incl. max wait time)	Verification Method 
(for testing)
-	The user gives a prompt containing the topic and the scope of the topic to be researched.	-	The AI tool asks for the topic to be researched – “Hi ------! Ready to help you with web research. Please provide a topic to start. ”
-	The user when prompted gives the topic and the AI agent then gives the research paper complete with a list of sources from where the research paper was generated from
-	The response time is standard and the latency is also standard during the course of testing	-	If the sources provided are accurate to the report generated
-	If the report generated is accurate and sufficient to the prompt provided 
-	If it follows the standard format for a research paper 




