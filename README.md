# Glossalia
application to gather language data for creating language courses

## Use cases  
This is a tool for those who want to help other people learning a language by providing them with data that they can export in order to create language courses on memrise, cerego.com etc. with. 
But it could also be useful for language researchers or translators. 
I know people who's first language isn't English and they often had it much harder finding free courses and vocab online. 
With this programm I want to contribute to changing that. Especially if the language you wish to learn is spoken by less than 0.5% of the [world's population](https://en.wikipedia.org/wiki/List_of_languages_by_number_of_native_speakers) this could be helpful *if* someone has already sat down create some data for you.

## The Idea
A multi-platform application which parses a paragraph of text (ideally from a non-copyright source) and divides it into lists of 
* sentences
* words
The sentences can then be fully parsed manually according to the language's grammar and new words be added to a dictionary. 
The sentences will include tags like the subject or context of that matter talked about. 
The dictionary will include information like word frequency to create effective vocab learning lists. 

## Long-term goals
* the more data is added for a given language pair the more reliably the program can pre-fill all it's properties 
* the data could be used in connection with artificial intelligence
* users should have the freedom to run Glossalia with their own db server or connect with hosted servers around the world to find the data they need for learning
* UI in many language available
* an overseas medical student should be able to learn mainly medical English if they want to study medicin based on tags. On the contrary such vocab and sentences should be excluded if you just want to learn conversational English.
* the community creates ports of this application in java, php, python etc. and also mobile platforms
* platforms like memrise or cerego can tab into the data and automatically create courses on their platforms

## Known challenges
* I always had problem setting up Entity Framework for MySQL. Depending on that I might have to create my own ORM.
* I'm self-taught and still a c# beginner. My code will not comply to current standards but any pull request for refactoring is welcome. 
* depending on the languages the db tables can all look slightly different. It has to be quite intelligent and flexible. 
* My dream is that those providing language data are native speaks and can also record themselves reading what they input (sentences and lemma separately). The question is how those files could be hosted.

## Other similar software
* nothing I'm aware of right now. please send links or comment
