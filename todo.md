# climb-backend TODO ENPOINTS

## Endpoints

===================
### GET /check_fb_id
###### + returns true if fb_id already in the database

===================
### POST /save_user_unlocks
###### + saves the user's amount of coins, the climber sprites they have
unlocked, and the spikeball sprites they have unlocked. The sprite unlock info
should be a dictionary of [String : Bool], where the string is the color (see
the UserDefaults I setup in GameViewController for reference).

===================
### GET /get_user_unlocks
###### + gets the user's unlock info (coins, climber sprites, spikeball sprites)

===================
### GET /get_friends_scores
###### + given user's fb_id, gets the user's friends scores returning
[(name, score)]

===================
### GET /get_global_scores
###### + gets the top 100 global scores