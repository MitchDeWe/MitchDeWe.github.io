# What makes a good dataset?
While I wait for the collab to run I can remark on some things that make a good dataset:

* Ensuring that the data you are putting into your dataset it categorically correct is very important. Say if I were to put a photo of a monkey in the 
whale dataset, since the data is only a small amount (<500) then this will likely cause the model to think that some monkeys are whales, not good.

* Another thing to consider if this were less of a random scrape would be that the data should be versitile, if I want to identitfy images of birds that are
flying and birds that arent as both being birds I need to have this in my dataset to reflect this also.

* train/validation/test is very important as it gives a reflection of what point the model is learning from the data and remembering the data, ideally the training, validation
and test have the smae accuracy at the end of training to indicate that the model doesn't have 'training bias'

Applying this for the assignment I have tried to choose animals that are very distinctly different such that the model will be able to identify them at a greater rate.
