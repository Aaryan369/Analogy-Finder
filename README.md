# Analogy-Finder
Analogies are a comparison between one word and another. Humans compare these words based on many factors like gender, is it a place, can we eat it, what is it's use and so on.
When it comes to machines they use similar procedure where each word has a set of attributes and it is rated within range -1 to 1.
Based on the relation between the first 2 words the algorithm will find the difference of attributes and their values and use them as reference to find the word that matches the third word from the list.
I have used a pre-trained Global vector for word representation that has word and its embeddings. Each word has 50 values and there are a total of 4,00,000 words in it's vocabulary.

**The Input can be given in form of**

![image of input](/Images/Ques.png)

After going through the entire dictionary 
**The answer is displayed as**

![image of output](/Images/Ans.png)
