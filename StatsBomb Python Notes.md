
# Competitions
## Competition IDs

``` json
{'1. Bundesliga': 9,
'Champions League': 16,
'Copa del Rey': 87,
"FA Women's Super League": 37,
'FIFA U20 World Cup': 1470,
'FIFA World Cup': 43,
'Indian Super league': 1238,
'La Liga': 11,
'Liga Profesional': 81,
'Ligue 1': 7,
'North American League': 116,
'NWSL': 49,
'Premier League': 2,
'Serie A': 12,
'UEFA Euro': 55,
'UEFA Europa League': 35,
"UEFA Women's Euro": 53,
"Women's World Cup": 72}
```

## Competition Seasons

``` json
{
'1. Bundesliga': 
	 ['2015/2016'] ,
'Champions League':
	 ['2018/2019', '2017/2018', '2016/2017', '2015/2016', '2014/2015', '2013/2014','2012/2013','2011/2012', '2010/2011', '2009/2010','2008/2009', '2006/2007','2004/2005' ,'2003/2004', '1999/2000','1972/1973', '1971/1972', '1970/1971'],
  
'Copa del Rey': 
	 ['1983/1984', '1982/1983', '1977/1978'],
 
"FA Women's Super League":
	['2020/2021','2019/2020','2018/2019'],
  
'FIFA U20 World Cup': 
	 ['1979'],
 
'FIFA World Cup': 
	['2022','2018','1990','1986','1974','1970','1962','1958'],
'Indian Super league': 
	['2021/2022'],
'La Liga': 
	['2020/2021', '2019/2020', '2018/2019', '2017/2018', '2016/2017', '2015/2016', '2014/2015', '2013/2014', '2012/2013', '2011/2012', '2010/2011', '2009/2010', '2008/2009', '2007/2008', '2006/2007', '2005/2006', '2004/2005', '1973/1974'] ,
'Liga Profesional': 
	['1997/1998', '1981'],
'Ligue 1': 
	['2015/2016'],
'North American League': 
	['1977'],
'NWSL': 
	['2018'],
'Premier League': 
	['2015/2016', '2003/2004'],
'Serie A': 
	['2015/2016', '1986/1987'],
'UEFA Euro': 
	['2020'],
'UEFA Europa League': 
	['1988/1989'],
"UEFA Women's Euro": 
	['2022'],
"Women's World Cup": 
	['2023', '2019']}

```

## Competition Columns
``` json
['competition_id', 'season_id', 'country_name', 'competition_name', 'competition_gender', 'competition_youth', 'competition_international', 'season_name', 'match_updated', 'match_updated_360', 'match_available_360', 'match_available']
```

# Seasons
## Season IDs


``` python
{'1958': 269,
 '1962': 270,
 '1970': 272,
 '1970/1971': 276,
 '1971/1972': 71,
 '1972/1973': 277,
 '1973/1974': 278,
 '1974': 51,
 '1977': 68,
 '1977/1978': 279,
 '1979': 274,
 '1981': 275,
 '1982/1983': 268,
 '1983/1984': 84,
 '1986': 54,
 '1986/1987': 86,
 '1988/1989': 75,
 '1990': 55,
 '1997/1998': 48,
 '1999/2000': 76,
 '2003/2004': 44,
 '2004/2005': 37,
 '2005/2006': 38,
 '2006/2007': 39,
 '2007/2008': 40,
 '2008/2009': 41,
 '2009/2010': 21,
 '2010/2011': 22,
 '2011/2012': 23,
 '2012/2013': 24,
 '2013/2014': 25,
 '2014/2015': 26,
 '2015/2016': 27,
 '2016/2017': 2,
 '2017/2018': 1,
 '2018': 3,
 '2018/2019': 4,
 '2019': 30,
 '2019/2020': 42,
 '2020': 43,
 '2020/2021': 90,
 '2021/2022': 108,
 '2022': 106,
 '2023': 107}
```



# Match Columns

``` python
['match_id', 'match_date', 'kick_off', 'competition', 'season', 'home_team', 'away_team', 'home_score', 'away_score', 'match_status', 'match_status_360', 'last_updated', 'last_updated_360', 'match_week', 'competition_stage', 'stadium', 'referee', 'home_managers', 'away_managers', 'data_version', 'shot_fidelity_version', 'xy_fidelity_version']
```
# Events

## Event Columns

``` python
['50_50', 'ball_receipt_outcome', 'ball_recovery_offensive', 'ball_recovery_recovery_failure', 'block_deflection', 'block_offensive', 'carry_end_location', 'clearance_aerial_won', 'clearance_body_part', 'clearance_head', 'clearance_left_foot', 'clearance_right_foot', 'counterpress', 'dribble_nutmeg', 'dribble_outcome', 'dribble_overrun', 'duel_outcome', 'duel_type', 'duration', 'foul_committed_advantage', 'foul_committed_card', 'foul_committed_offensive', 'foul_committed_type', 'foul_won_advantage', 'foul_won_defensive', 'goalkeeper_body_part', 'goalkeeper_end_location', 'goalkeeper_outcome', 'goalkeeper_position', 'goalkeeper_technique', 'goalkeeper_type', 'id', 'index', 'interception_outcome', 'location', 'match_id', 'minute', 'off_camera', 'out', 'pass_aerial_won', 'pass_angle', 'pass_assisted_shot_id', 'pass_body_part', 'pass_cross', 'pass_cut_back', 'pass_deflected', 'pass_end_location', 'pass_goal_assist', 'pass_height', 'pass_inswinging', 'pass_length', 'pass_miscommunication', 'pass_no_touch', 'pass_outcome', 'pass_outswinging', 'pass_recipient', 'pass_shot_assist', 'pass_switch', 'pass_technique', 'pass_through_ball', 'pass_type', 'period', 'play_pattern', 'player', 'player_id', 'position', 'possession', 'possession_team', 'possession_team_id', 'related_events', 'second', 'shot_aerial_won', 'shot_body_part', 'shot_end_location', 'shot_first_time', 'shot_freeze_frame', 'shot_key_pass_id', 'shot_one_on_one', 'shot_open_goal', 'shot_outcome', "shot_statsbomb_xg", 'shot_technique', 'shot_type', 'substitution_outcome', 'substitution_replacement', 'tactics', 'team', 'team_id', 'timestamp', 'type', 'under_pressure']
```

## Event Notes

### Types

``` json
"Starting XI",
"Half Start",
"Pass",
"Ball Receipt*",
"Carry",
"Duel",
"Pressure"
"Miscontrol",
"Clearance",
"Ball Recovery",
"Interception"
"Block",
"Foul Committed",
"Foul Won",
"Dribble",
"Dispossessed",
"Shot",
"Goal Keeper",
"Tactical Shift"
"Dribbled Past",
"Injury Stoppage",
"Half End",
"Substitution",
"Referee Ball-Drop",
"Own Goal Against",
"Own Goal For"
```
