# # Using LLMChain
The LLMChain is most basic building block chain. It takes in a prompt template, formats it with the user input and returns the response from an LLM.

To use the LLMChain, first create a prompt template. 
We can now create a very simple chain that will take user input, format the prompt with it, and then send it to the LLM.

# Math chain
This notebook showcases using LLMs and Python REPLs to do complex word math problems.

# Bash chain
This notebook showcases using LLMs and a bash process to perform simple filesystem commands.

# Router
This notebook demonstrates how to use the RouterChain paradigm to create a chain that dynamically selects the next chain to use for a given input.

Router chains are made up of two components:

The RouterChain itself (responsible for selecting the next chain to call)
destination_chains: chains that the router chain can route to
In this notebook we will focus on the different types of routing chains. We will show these routing chains used in a MultiPromptChain to create a question-answering chain that selects the prompt which is most relevant for a given question, and then answers the question using that prompt.
