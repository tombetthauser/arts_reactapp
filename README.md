# arts_reactapp
A MERN app helping artists find each other and organize studio visits through a matching structure similar to a dating application.

## Database Tables -- for separate Open Arts API
1. users -- types: (artists, gallerists, collectors)
2. artworks -- title, size, medium, date, images
4. matches -- liker_user_id / liked_user_id -- a match requires both (ie 3/7 and 7/3)
5. chats -- user1_id / user2_id / ???
6. chat_messages -- author / text / time / ???
7. galleries -- name / address / website / phone / etc -- for webscraper not match app
8. shows -- gallery / artists / date / images
7. ???
