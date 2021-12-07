# NolanJolicoeur.github.io

## Understanding the data 

- Game id- randomly generated id for each player in each game they played
- player id- an id that is consistent with the player throughout the data set
- pos - Stands for position and signifies which position that specific player plays
- player - Contains the name of the player who's stats are being represented
- team - Abbreviated team name refering to the team each player is on
- pass_cmp - Passes completed 
- pass_att = Passes attempted
- pass_yds - Passing yards 
- pass_td - Passing touchdowns 
- pass_int - Passes intercepted 
- pass_sacked - Times sacked 
- pass_sacked_yards - Yards lost off sacks 
- pass_long - Longest pass of the game 
- pass_rating - Calculated rating of how efficient a passer is 
- rush_att - Attempted rushes 
- rush_yds - Rushing yards 
- rush_td - Rushing touchdowns 
- rush_long - Longest run of the game 
- targets - Number of intented passes thrown to player 
- rec - Number of catches or receptions 
- rec_yds - Number of receiving yards 
- rec_long - Longest catch of the game 
- fumbles_lost - Number of times the player fumbles and the other team recovered it 
- rush_scrambles - Number of times the QB scrambled out of the pocket and ran the ball (The QB ran the ball on a play that was designed for them to pass it)
- designed_rush_att - Designed running plays for the player
- comb_pass_rush_plays - Combined rushing and passing plays called for player 
- comb_pass_play - Total number of plays intended to pass the ball 
- comb_rush_play - Total number of plays intended to run the ball 
- Team_abbrev - Current abbreviation of team the player is playing for 
- Opponent_abbrev - Abbreviation of team the player is facing 
- two_point_conv - Converted two point conversions scored by the player 
- total_ret_td - Kicks returned for touchdowns 
- offensive_fumble_recovery_td - Fumbles that were recovered by the offensive team and resulted in a touchdown 
- pass_yds_bonus - Extra fantasy points given out for throwing for a specified number of yards 
- rush_yds_bonus - Extra fantasy points given out for running for a specified number of yards 
- rec_yds_bonus - Extra fantasy points given out for receiving the ball for a specified number of yards 
- Total_DKP - Draft Kings fantasy points 
- Off_DKP - Offensive Draft Kings fantasy points
- Total_FDP - Fanduel fantasy points 
- Off_FDP - Offensive Fanduel fantasy points 
- Total_SDP - Standard rules fantasy points 
- Off_SDP - Offensive fantasy points by standard rules 
- pass_target_yds - Passing yards that connect with target 
- pass_poor_throws - Bad passes that miss the target
- pass_blitzed - Number of times the player is blitzed by the defense 
- pass_hurried - Number of times the player is hurried when throwing the ball 
- rush_yds_before_contact - Rushing yards before any contact from a defensive player 
- rush_yac - Running yards after contact from a defensive player 
- rush_broken_tackles - Number of broken tackles by the rusher

- I chose to use Total_DKP because there style of point calculation is the most popular in fantasy football leagues 
- I also created my own data set of teams records in the R-markdown file because if I took one from online it would keep updating and would not stay relivant to this data set whish I downloaded on November 29, 2021

  
