Ignore notebook 01. It's just for nicely organizing all the data.

Used this competition as an opportunity to gets my hands wet with transfer learning. Seems pretty interesting. I tried the VGG16, VGG19, Inception-ResNet and the ResNet50. Mostly worked on VGG16 and ResNet50. 

ResNet50 had the best out of the box accuracy so I decided to go ahead and tune that. Manage to go from about 91% to 93.69%. Found this competition pretty late so couldn't spend too much time on it. The main difference in accuracy came from adjusting the learning rate and adding decay.

I ran most of the models on my own system with a 1050Ti 4GB. It took about 2-3 mins/epoch. For the final model, I trained it on a Kaggle kernel for 20 epochs.

Leaderboard Ranking: 147/313 with 92.604%. 1st place was at 95.597%.