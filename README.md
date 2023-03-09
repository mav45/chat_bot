# chat_bot
Very basic chatbot script using an input/output training set with tensorflow. 
Sample of data.csv:

"hello","hi"
"How can I help you today?","I am trying to get information regarding your latest release."
"Would you like a website link?","I'd rather you told me about it."
"My pleasure. What would you like to know?","When was the exact release date?"
etc...

Note that there are no column headers. The script builds them for you.

I had issues with the version of Tensorflow that I was running. I had to run this in a virtual environemnt as it required the latest version of Tensorflow and 
I didn't want that to interfere with other scripts that I am running.
