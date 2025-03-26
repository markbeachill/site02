---
author: ["Mark Beachill"]
title: "Prompt - create teaching materials"
date: "2025-03-23"
description: "Prompt to create teaching materials for a mistakes"
summary: "Prompt will create customised teaching materials for a mistakes"
tags: ["markdown", "syntax" ]
categories: ["prompts", "show-errors"]
series: ["Prompts Guide"]
ShowToc: true
TocOpen: true
social:
  fediverse_creator: "@mark@mark.social"
---

### What it does

The prompt creates personalised teaching materials based on fixing a mistake. It is ideal for those who want to improve their writing and make sure they understand and cut out errors.  

For a mistaek it produces: - Explanation of the mistake. - Examples of similar mistakes and their corrections. - Test questions and answers.-  Discussion of this type of mistake, why it happens and what can be done to stop it.

### Instructions

**Option 1. Run using an error found in the "show errors" prompt.**

In a chatbot such as ChatGPT, Claude or Grok etc.  Run the ["show errors" prompt](https://markbeachill.github.io/site02/posts/prompt-show-errors/) on a piece of your writing. Look at the mistakes it identifies - they are numbered. Find one you want to fix. Make a note of the paragraph and the mistake number.

Continue - in the same chat window. Copy the prompt below.

Edit the end. Where the prompt says: "The mistake to focus on is MISTAKE NUMBER", replace this your paragraph number and error number. For example, your edit might say; "The mistake to focus on is **mistake 3 in paragaraph 1.**" Run the prompt.

**Option 2. Use an example error you have found.****

Find a sentence with an  error and create a very brief description of that error.
For example, "The trial took place at the central criminal court". The description of the error would be: "incorrect capitalisation".

Copy the prompt below. In a chatbot such as ChatGPT, Claude or Grok etc.  paste the prompt.
Edit the end of the prompt.  Where it says: "The mistake to focus on is MISTAKE NUMBER", replace this with: "The mistake to focus on is "YOUR SENTENCE" (YOUR EXPLANATION).

Based on the error this would be: "**The mistake to focus on is "The trial took place at the central criminal court" (incorrect capitalisation)"**. Run the prompt. 

**And then?**
Go through the teaching material and test yourself. You may want to copy and save the teaching materials so you go through them again later. 

### Sample output

For the prompt with this at the end:
*The mistake to focus on is "The trial took place at the central criminal court" (incorrect capitalisation).* 

Absolutely! Here's the full teaching material on the **incorrect capitalisation** in the sentence _"The trial took place at the central criminal court,"_ using plain text only and no symbols or emojis:

----------

### <span style="color:blue;">Teaching Materials: Capitalisation of Proper Nouns</span>

### <span style="color:blue;">A) Explanation of the Mistake</span>

The sentence **"The trial took place at the central criminal court"** contains a capitalisation error.

The phrase **"central criminal court"** refers to a specific, official institution—the **Central Criminal Court**—which is a proper noun. In English, **proper nouns** are the official names of particular people, places, organisations, or things, and they must begin with capital letters.

Because "Central Criminal Court" is the formal name of a specific court, each word in the name should be capitalised.

**Corrected sentence**:  
**"The trial took place at the Central Criminal Court."**

If the sentence were referring to courts in general (not naming a specific one), lowercase would be appropriate. But in this case, it is the name of a particular legal institution in London, so it needs capitalisation.

----------

### <span style="color:blue;">B) Glossary of Terms</span>

**Capitalisation**  
The use of capital (uppercase) letters. In English, we use capital letters for the first word in a sentence and for proper nouns.

**Proper noun**  
A noun that names a specific person, place, organisation, or thing. Proper nouns always begin with capital letters. Examples include "London", "Tesco", and "Queen Elizabeth".

**Common noun**  
A noun that refers to a general class of people, places, or things. These are not capitalised unless they start a sentence. Examples include "city", "court", and "teacher".

----------

### <span style="color:blue;">C) Examples of Similar Mistakes and Corrections</span>

1.  Incorrect: _She studies law at the university of Oxford._  
    Correct: _She studies law at the University of Oxford._
    
2.  Incorrect: _They visited the tower of london on holiday._  
    Correct: _They visited the Tower of London on holiday._
    
3.  Incorrect: _The president met with the prime minister at downing street._  
    Correct: _The President met with the Prime Minister at Downing Street._
    

Each of these errors involves failing to capitalise proper nouns such as official place names or titles.

----------

### <span style="color:blue;">### D) Test Questions</span>

Correct the capitalisation in the following sentences:

1.  the ceremony was held at buckingham palace.
    
2.  he took his driving test at the department for transport.
    
3.  the report was submitted to the house of commons.
    
4.  the statue is located in trafalgar square.
    
5.  she got a job offer from the london school of economics.
    

----------

### <span style="color:blue;">E) Answers for Test Questions</span>

1.  The ceremony was held at Buckingham Palace.
    
2.  He took his driving test at the Department for Transport.
    
3.  The report was submitted to the House of Commons.
    
4.  The statue is located in Trafalgar Square.
    
5.  She got a job offer from the London School of Economics.
    

----------

### <span style="color:blue;">F) Discussion of This Type of Error Based on Key Texts</span>

Writers like Lynne Truss (_Eats, Shoots & Leaves_) and resources such as _The Oxford A–Z of Grammar and Punctuation_ highlight the importance of accurate capitalisation in formal writing. Capital letters help distinguish **proper nouns** (specific names) from **common nouns** (general references). When proper nouns are not capitalised, it can lead to confusion or make writing appear careless and informal.

In academic, professional, and legal contexts, accuracy in capitalisation contributes to clarity and respect for official institutions, people, and places.

----------

### <span style="color:blue;">G) Reasons Why These Mistakes Are Made and What Can Be Done About Them</span>

**Why do students make this mistake?**

-   Some names, like "central criminal court", **sound like descriptions**, not official titles, which can make it unclear whether to capitalise them.
    
-   In **speech**, there’s no visible capitalisation, so students may not notice the difference in writing.
    
-   **Titles of institutions** can be long and unfamiliar, making it harder to spot that they are proper nouns.
    

**What can be done to improve?**

-   **Ask yourself**: Is this the official name of a specific place or organisation? If so, capitalise it.
    
-   **Double-check unfamiliar names**: A quick search can confirm whether a phrase is a formal title.
    
-   **Practise editing**: Go through writing with a focus only on capitalisation—this builds awareness and helps reinforce the rules.
    

----------


### Copy prompt (UK English)
(click copy on top right)

```{hl_lines=[4,8]}
Context: I am a student who needs help to improve my writing. I do not want you to do all the work for me. I want help so I don’t make the same mistakes again.

Role: You are a personal writing tutor in the UK.

Actions and format:

Act as a writing tutor in the UK. Your task is to create teaching materials based on a specific mistake in the piece of writing. The teaching materials should be written in plain English and explain any jargon that is required.

The teaching materials should include:

A) A detailed explanation of the specific mistake: Explain what was incorrect in the original sentence, why it was incorrect, and how it can be corrected.
B) A simple glossary of any grammatical terms used in this explanation. Use at most two sentence for each item in the glossary.
C) Examples of similar mistakes being corrected: Provide at least three examples of sentences with similar errors and their corrections.
D) Test questions: Create at least three test questions where students need to identify and correct these types of errors.
E) Answers for test questions: Show the answers to the three text questions.
F) A discussion of this type of error based on key texts about writing
G) Reasons why these mistakes are made and what can be done about them.

The mistake to focus on is MISTAKE NUMBER.


```

### Copy prompt (US English)
(click copy on top right)

```{hl_lines=[4,8]}
Context: I am a student who needs help to improve my writing. I do not want you to do all the work for me. I want help so I don’t make the same mistakes again.

Role: You are a personal writing tutor in the USA.

Actions and format:

Act as a writing tutor in the UK. Your task is to create teaching materials based on a specific mistake in the piece of writing. The teaching materials should be written in plain English and explain any jargon that is required.

The teaching materials should include:

A) A detailed explanation of the specific mistake: Explain what was incorrect in the original sentence, why it was incorrect, and how it can be corrected.

B) A simple glossary of any grammatical terms used in this explanation. Use at most two sentence for each item in the glossary.

C) Examples of similar mistakes being corrected: Provide at least three examples of sentences with similar errors and their corrections.

D) Test questions: Create at least three test questions where students need to identify and correct these types of errors.

E) Answers for test questions: Show the answers to the three text questions.

F) A discussion of this type of error based on key texts about writing

G) Reasons why these mistakes are made and what can be done about them.

The mistake to focus on is MISTAKE NUMBER.


```


### Full text of the prompt
Context: I am a student who needs help to improve my writing. I do not want you to do all the work for me. I want help so I don’t make the same mistakes again.

Role: You are a personal writing tutor in the UK.

Actions and format: Act as a writing tutor in the UK. Your task is to create teaching materials based on a specific mistake in the piece of writing. The teaching materials should be written in plain English and explain any jargon that is required.

The teaching materials should include:

A) A detailed explanation of the specific mistake: Explain what was incorrect in the original sentence, why it was incorrect, and how it can be corrected.

B) A simple glossary of any grammatical terms used in this explanation. Use at most two sentence for each item in the glossary.

C) Examples of similar mistakes being corrected: Provide at least three examples of sentences with similar errors and their corrections.

D) Test questions: Create at least three test questions where students need to identify and correct these types of errors.

E) Answers for test questions: Show the answers to the three text questions.

F) A discussion of this type of error based on key texts about writing

G) Reasons why these mistakes are made and what can be done about them.

The mistake to focus on is MISTAKE NUMBER.
