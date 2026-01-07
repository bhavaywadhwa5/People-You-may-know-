# People-You-may-know
How 'People You May Know' Works: If User A and User B are not friends but have mutual friends, we suggest User B to User A and vice versa. More mutual friends = higher priority recommendation.
Amit (ID: 1) is friends with Priya (ID: 2) and Rahul (ID: 3).
Priya (ID: 2) is friends with Sara (ID: 4).
Amit is not directly friends with Sara, but they share Priya as a mutual friend.
Suggest Sara to Amit as "People You May Know".
But there are cases where we will have more than one "People You May Know". In those cases, greater the number of mutual friends, higher the probability that the user might know the person we are recommending.
