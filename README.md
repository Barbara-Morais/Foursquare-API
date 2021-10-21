# Foursquare-API
Extra work done in Bootcamp.

RECOMMENDING HOTELS BASED ON NEARBY PLACES - CLUSTERING APPROACH

New York is my dream trip, so I decided to use Data Science to choose the perfect hotel for me. This project will segment all possible accommodation hotels on the trip, and then create a system to suggest them based on nearby establishments, thus seeking to increase the probability of high destination satisfaction.

OBS.: Between the explanation, "With the classification carried out, we can suggest the top 5 Hotels by rating for the cluster found", I delete the code that was before this, to find the perfect cluster:
#cluster = kmeans.predict(merge_df)[0].item()
#print("Os hotéis em New York a serem indicados ao cliente pertencem ao cluster {}".format(cluster))
