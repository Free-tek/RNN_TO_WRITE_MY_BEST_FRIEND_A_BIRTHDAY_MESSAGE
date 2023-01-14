# RNN_TO_WRITE_MY_BEST_FRIEND_A_BIRTHDAY_MESSAGE
Its my bestfriends birthday and as our usual tradition we write codes to each other to wish ourselves happy birthday. 
So this i decided to up my game, i wrote him an RNN model that could always write him a birthday message once he clicked enter on the predict line.
Here was my approach.
<br>
1. I swept my phone for all the birthday messages i had, which wasnt still enough to build a model.
2. I checked the internet for more birthday messages and then i built the model, but the model still performed poorly, here was the ouput
<br>
Happy birthday to mest and the berthat you and your birthday to the berthea soul the and me and and the thea so meat to mest and I way the berthan the berthe berther and you and your birthday, I wast day to me to the for and you ar that so meat and your berthday to the berthday to mest and your I way to lof the berthes and you and you and you and your berthe berthat your birthday to mes mo thear and you and your meat the berthe and you and your and thar your of and you and your meat to the berther on thar the more the berthea sout birthday to mest and your that to the berthe for and you and you and the me that and your birthday to and your and your birthday to mece and you and you for hat you and your meat to the and you and you and your and you and you and the birthday to my birthday to mest and your birthday to more to mess and the berthan than to mes and you and your ond your berthday to the and you and you and your berthday to mest birthday to mathe berthea to mant so mest and your birthday to me
<br>
3. I knew i had to do better, i was thinking of duplicating the messages i used to train the model but just copying and pasting it 
twice will be a waste since its thesame thing as training the model on an extra epoch, so i used an online paraphrasing tool to
re praphrase all the messagesz i had and i added it to the previous corpus but...
<br>
4. The model was still predicting badly, here is what it predicted
<br>
Happy birthday to you a love you a love you a love you a love you a lear the best and you are the best of and and and a conting and a dear to the mest of your birthday to you and the mest of you are as and and as in the best to me. 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

I wish a wisher as and and a beat to me. 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
5. The model was still not good enough, i was scared ill not be able to present my friend a code for his birthday gift, but i had the eureka momnet after some hours

6. I reparaphrased all my corpus on another reparaphrasing tool and my corpus almost doubled in lines, so i trained the model

<br>

7. The loss went down to about 0.78 compared to 1.3 on previous models and i had a more reasonable birthday message.
<br>

Happy birthday to my best friend that you simply have got a shock in the foremost of your distinctive day of yours be some person I hope you have got a good day.
- - - - - - -
“I hope you have got a good day.

- - - - - - -
"I trust you have got a good day.

- - - - - - -
“Happy Birthday to my best pal! I trust you have got a good day.

- - - - - - -
“I hope you have got a good day. Hope your birthday is brimful with fun and laughter. Have a beautiful birthday to my best pal! I trust you have got a good day.
- - - - - - -
“I hope you have got a good day.

- - - - - - -

"I trust you have got a good day.

- - - - - - -
“I hope you have got a good day. Hope your birthday is as astounding one for a prosperous years and see an opportune to recollect you have got a good day. 

- - - - - - - - -
“I hope you have got a good day.

- - - - - - -
“I hope you have got a good day.

-
