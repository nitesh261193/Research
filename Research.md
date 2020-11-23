# Research 

#### Few projects are already developed in Conversational-chatBot area. The findings of developed projects are-

Exploring the feasibility of extraction of text from sample operating manuals and storing them in a database, developing a chatbot interface for the user to query and fetch stored information, and front-end UI. Based on the ease of setting up a conversational agent, built-in functionalities and a powerful Natural Language Processing (NLP) algorithm, DialogFlow from Google was chosen as the chatbot platform. Due to a schema-less structure and scalable architecture, Datastore from Google Cloud Platform (GCP) was chosen as the database to host the texts extracted from manuals. The front-end was developed in AngularJS and integrated with Django-run backend which performed the important task of fetching replies for user queries. The entire project was hosted and run on Google Cloud with the application running on-demand on GCP’s App Engine

### Objectives
• Design a conversational-style chatbot with which the user can interact to query topics from operating manual of medical devices

• Explore a mechanism to extract topics and texts from the PDF of these operating manuals for querying purpose

• Develop a method to display responses to users in chatbots interface for lengthy topics

### Preproccesing
The powerful Natural Language Toolkit (NLTK) library in python has a list of stopwords which can be used to filter out a sentence containing them to unnecessary garbage data. The NLTK library also contains the popular stemming algorithm called Porter Stemmer capable of stemming all the words in the sentence. The outcome of such a filtering system is a clean data that can be indexed and used to build reliable ML models

###Limitation
Loss of contextual meaning renders the data incomprehensible after preprocessing. There is also a probability that the words which do not need any stemming getting cleaned and triggering false reponses

###Details of Various ChatBot 
#####1. Aerospace ChatBot
Most of the traditional "business metrics" for conversational agents
are linked to web-based/B2C applications. The specificity of the
aerospace context excludes the applicability of most of these classical
approaches. Classical approaches mostly rely on retention and
engagement metrics, related to the business goals and/or commercial
funnel. Research in conversational agents has emerged from
multiple academic domains in parallel and naturally each of the
domains have adopted their own evaluation approaches. Among
multiple proposals made, four major perspectives stand out in the
literature

Information Retrieval (IR) approaches are applicable to question/
answering conversation. These focus on utility, relevance and
timeliness aspects of the answers given to the user based on a problem
statement. Precision, recall and related variants based on hit@k
measures are all valid in this context. It does not encompass the
conversation aspects but offer a clearer evaluation of strict utility

NLP puts emphasis on conversation and cooperation with human discourse. 
In these evaluation protocols, the quality and coherence of the discourse are often weighted
against a topical categorization of the conversations

User experience (UX) methodology is based on
the human factors perspective and usability from the user pointof-
view. This is the approach that better takes into account the
end user perspective due to their direct involvement. However, it
requires to setup interactive evaluations that can be time consuming
and complex in terms of logistics, unless one already has an online
system.

###Alexa 
The task itself consists of voice-to-voice interactions and the
competition offers a mix of evaluation and data collection
through randomized human-to-bot conversations. An existing
dataset of over 1 million conversations is distributed to
the participants who are expected to develop their bots with
the Alexa SDK

###CommAI-env (Environment for Communication-based AI)
It is an initiative from Facebook for training and evaluating AI
systems (agents). The data exchange occurs as bit-level stream - even
if the online running mode assumes the bits are characters
in standard encoding for display purposes. The agents are
trained by exposing them to various tasks and evaluated by
considering the average reward accumulated by the agent
just like in a Reinforcement Learning framework

### ParlAI
It currently contains a lot of academic
tasks, covering a broad scope of use-cases1: QA, goal-oriented
chat (eg. booking), chitchat, negotiation, visual QA, cloze deletion
tes

### Task/datasets performed by ChatBot
#####SQuAD Stanford Question Answering Dataset 
20 questions
collected from crowd-workers on a set of Wikipedia articles,
where the answer to every question is a segment of text, or
span, from the corresponding reading passage. It contains
100k+ question-answer pairs on 500+ articles. There is however
no notion of dialog nor construction of response in natural
language and the questions are mostly fact-based.

##### bAbI 
the aim is that each task tests a unique
aspect of text and reasoning, and hence tests different capabilities
of learning models. Each QA instance consists of a set
of sentences stating facts,

##### CLEVR
aim at testing various aspects of visual reasoning
including attribute identification, counting, comparison,
spatial relationships, and logical operations

##### MSMARCO
large scale dataset for reading comprehension
and question answering. It comprises a large set of more
than 1M real user queries from Bing search engine, more than
100k natural language answers or no answer subset over 10
text passages per query

##### WikiQA 
set of question and sentence pairs, collected and
annotated for research on open-domain question answering.
Each question is linked to a Wikipedia page that potentially
has the answer

##### Movie Dialog dataset
goal and non-goal oriented dialog
centered around the topic of movies [6]. It combines 3 types
of tasks: question answering, recommendation and discussion


##### Ubuntu dialog 
offers 1M dialog with roughly 8 turns each (on average, with a minimum of 3 turns and a few
cases with dozens of turns) between 2 users. It comprises 7M
utterances using 100M words of vocabulary.

##### Textbook Question Answering
dataset is drawn from middle school science curricula as described in [10]. It
consists of 1, 076 lessons from Life Science, Earth Science and
Physical Science textbooks. Each lesson has a set of multiple
choice questions that address concepts taught in that lesson

##### HotpotQA
composed of 113kQApairs based on Wikipedia;
questions are designed to require multi-hop reasoning

##### Google’s Natural Questions 
is a QA dataset, whose questions
consist of real users’ queries issued to the Google search
engine [11]. An annotator is presented with the top 5 search

##### QuAC
provides 14k dialogues that encompass questions
over Wikipedia. The definition of questions and answer is
similar to the SQUAD dataset


###Metrics to test
The need for precision tends to favor traditional information retrieval
metrics (precision, recall, f-measure[4]). Regularly used in
most QA and search tasks, these measures allow an absolute measurement
of performance of the agent. They need an unambiguous
supervision signal given as a set of search tasks and exact responses
which could be tedious to build

• engagement through number of dialog turns and conversation
duration

• coherence measured through Response Error Rate :
RER = number of non coherent responses/number of utterances

• conversational depth as the average number of consecutive
turns on the same topical domain


### ideal framework
The ideal framework, according to its creators, is consisting of three layers, the “perception, cognition and presentation layer” and supports mainly eight features: “self-consciousness, humorous, purity, IQ, EQ, memory, self-learning and charisma”. In the same study the importance of interactivity and machine learning existence between user and chatbot, the analytics ability and the interactivity in a sequence neural network or a framework, which follows the basic assistive model “dialogic, rational and
embodied agent” are recorded (Wei et al., 2018).

Another cognitive framework proposes that an efficient chatbot should consist of the “dialog manager”, who controls the conversational flow and “natural language” between bot and the user, which may be supported by either text or voice messages

The “inference engine” that extracts user intentions using the knowledge base; the “knowledge base” that supports conclusions and scheduling; the “planner” that executes the users’ orders and can always provide an alternative solution if chatbot doesn’t find the exact answer

effectiveness, efficiency and satisfaction

###Tools

As in other similar platforms the developers of Amazon Lex will pay for the usage they will have, meaning the number of the texts or the voice requests they will have. There is also the option to try Amazon Lex for free and from the date you start using it, you can process up to 10,000 text requests and 5,000 speech requests per month

Botkit is a framework provided free of charge, with a tested code, that implements parts of Microsoft Bot Framework (such as integrated NLP from LUIS.ai (for its paid version) and is supported from a big developers’ community. This set of tools obtain open libraries and visual conversation builder to assist the developers when building chatbots, apps and custom integrations for significant communication platforms (such as Slack, Facebook Messenger and Cisco Spark) and can be upgraded with the use of lots of plug-ins

Dialogflow uses Google's machine learning, creates chatbots based on common language conversations and it runs on the Google Cloud Platform to store your data. Furthermore, it can connect to users on Google Assistant, Alexa, mobile apps, Messenger, Twitter, websites and more.Dialogflow is a closed system with API (Application Programming Interface) and web interface. It can support Java, Python and Node js among other languages (Geekflare, 2020). It is quite user friendly as it does not require tech knowledge from the user, because nearly everything is accessible in the user interface. It does not need installation and can support more than 20 human languages. Some of other Dialogflow's features are the multiple channel options, on screen chats and speech recognition

### ChatBots capabilities
Chatbots provide a communication channel to correspond to customer needs through messaging in a predetermined scaled conversation. They interact with the customers in order to help them through a set of questions to gather valuable information and provide them most suitable solution, service or product

Chatbots have a wide area of knowledge but have improved also the capability of learning from their mistakes

Along with remembering the user’s data, bots can nowadays adjust their language and tone of voice based on the content of discussion, acknowledging personalization and an even more advance user experience.

###chatbot limitaion
Despite the advantages of adapting artificial intelligence in chatbot technology it seems that chatbots are still in early stage and they have not yet reached the utmost of their capabilities in customer satisfaction. Most of the chatbot tools are programmed in certain set of responses and answers


###Abstract
Results show that chatbots which are part of the instant messaging application are still in its early stages to become artificial
intelligence teaching assistants. The findings provide tips for teachers to integrate chatbots into
classroom practice and advice what types of chatbots they can try out.

#### Intro
Current developments in this area suggest that interaction with technologies,
either by natural language or by speech, is possible because technology develops, and users become more used to interacting
with digital entities. Rather than creating a human-like smart machine application, it is about creating effective digital assistants who
are able to provide information, answer questions, discuss a specific topic, or perform a task.A vast number of simpler and more domain-specific
text-based chatbots complement target-specific functionalities such as raising support tickets to leave feedback, disseminating content
for publishing sites, booking a hotel room, making a restaurant reservation, etc

### Purpose
The purpose of this study was to explore the use of a chatbot in the instant messaging tool to support learning. The two following
research questions were addressed in this study:
Research Question 1: What is the distribution of subject matter, use of language and development environment in chatbots on the
Facebook Messenger platform?
Research Question 2: What is the quality of educational chatbots on the Facebook Messenger platform?

### ABSTRACT
The purpose of this paper is to discuss about smart learning environments and present the FIT-EBot, a chatbot, which automatically gives a reply to a question of students about the services provided by the education system on behalf of the academic staff. The chatbot can play the role of an intelligent assistant, which provides solutions for higher-education institutions to improve their current services, to reduce labor costs, and to create new innovative services. Various artificial intelligence techniques such as text classification, named entity recognition are used in this work to enhance the system performance

### motivation
a) Students asking questions repeated frequently such as discipline, programs, regulations, scholarships, registration, courses, assignments, etc.;
task like leaning subject, exercises, course registration, course schedules, assignments, scholarships, regulations, etc

b) Searching information is often difficult and time consuming;

c) Huge workload for administrative staff and lecturers to manually answer each student’s questions, even impossible 


### Abstraction for Voice chatBot

Chatbots are programs that mimic human conversation
using Artificial Intelligence (AI). It is designed to be the
ultimate virtual assistant, entertainment purpose, helping one to
complete tasks ranging from answering questions, getting driving
directions, turning up the thermostat in smart home, to playing
one’s favorite tunes etc. Chatbot has become more popular in
business groups right now as they can reduce customer service
cost and handles multiple users at a time. But yet to accomplish
many tasks there is need to make chatbots as efficient as possible.
To address this problem, in this paper we provide the design of a
chatbot, which provides an efficient and accurate answer for any
query based on the dataset of FAQs using Artificial Intelligence
Markup Language (AIML) and Latent Semantic Analysis (LSA).
Template based and general questions like welcome/ greetings
and general questions will be responded using AIML and other
service based questions uses LSA to provide responses at any time
that will serve user satisfaction. This chatbot can be used by any
University to answer FAQs to curious students in an interactive
fashion

#### Emotion Synthesis
Similar to using voice, text, and facial cues for identifying affect, the same modalities can be used to make meaningful, contextual responses.
Speech synthesizers generally output text in a neutral, declarative style and monotonic fashion. By changing the patterns of stress and vocal intonations in speech, different kinds of emotions can be expressed. Vocal intensity increases for anger and decreases for sadness; speech rate is faster for anger, happiness and fear than for sadness.
Speech Synthesis Markup Language (SSML) is an XML-based markup language for speech synthesis. Using SSML tags, one can customize the pitch, speaking rate, volume of text, pausing, specify pronunciations, and add or remove emphasis for generating natural-sounding speech. Alexa and Google Assistant support the use of SSML for constructing output speech, and IBM has introduced expressive SSML tags in their text-to-speech services.
As in the example below, the tags can either set a positive, regretful, or neutral tone for the generated audio by setting the “express-as” tag with the expected expression