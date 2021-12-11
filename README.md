# GenderDectection_HA
Classification of twitter users by gender using a hierarchical attention model

A classification of tweet users was done by their gender using several deep learning models that use a GRU cell. 

The models are:

1. Classify all user tweets by making a big string of them and feeding that to a simple GRU based model.
2. Classify all user tweets by making a big string of them and feeding that to a GRU with attention based model.
3. Classify tweet by tweet using a simple GRU based model and then feed that as input of a voting system.
4. Classify tweet by tweet using a GRU with attention based model and then feed that as input of a voting system.
5. Classify a user profile using hierarchical attention, first at a word embedding level and then at a tweet level to codify all this information into the user profile.
