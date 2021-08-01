# Results and stats football games

This contains Serie A, Bundesliga and Premier League results and stats, craped from .

Data are available in the following format: 

- [x] CSV
- [x] JSON
- [x] RData (R language)

All results and stats are split by season and an unique file (`serie_a`, `premier_league`, `bundesliga`) is also provided with all seasons.

## Seasons

| Season    |      Serie A       |     Bundesliga     |   Premier League   |
| --------- | :----------------: | :----------------: | :----------------: |
| 1986/1987 | :heavy_check_mark: |                    |                    |
| 1987/1988 | :heavy_check_mark: |                    |                    |
| 1988/1989 | :heavy_check_mark: |                    |                    |
| 1989/1990 | :heavy_check_mark: |                    |                    |
| 1990/1991 | :heavy_check_mark: |                    |                    |
| 1991/1992 | :heavy_check_mark: |                    |                    |
| 1992/1993 | :heavy_check_mark: |                    |                    |
| 1993/1994 | :heavy_check_mark: |                    |                    |
| 1994/1995 | :heavy_check_mark: |                    |                    |
| 1995/1996 | :heavy_check_mark: |                    |                    |
| 1996/1997 | :heavy_check_mark: |                    |                    |
| 1997/1998 | :heavy_check_mark: |                    |                    |
| 1998/1999 | :heavy_check_mark: |                    |                    |
| 1999/2000 | :heavy_check_mark: |                    |                    |
| 2000/2001 | :heavy_check_mark: |                    |                    |
| 2001/2002 | :heavy_check_mark: |                    |                    |
| 2002/2003 | :heavy_check_mark: |                    |                    |
| 2003/2004 | :heavy_check_mark: |                    |                    |
| 2004/2005 | :heavy_check_mark: |                    |                    |
| 2005/2006 | :heavy_check_mark: |                    |                    |
| 2006/2007 | :heavy_check_mark: |                    |                    |
| 2007/2008 | :heavy_check_mark: |                    |                    |
| 2008/2009 | :heavy_check_mark: |                    |                    |
| 2009/2010 | :heavy_check_mark: |                    |                    |
| 2010/2011 | :heavy_check_mark: |                    |                    |
| 2011/2012 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2012/2013 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2013/2014 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2014/2015 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2015/2016 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2016/2017 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2017/2018 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2018/2019 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2019/2020 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| 2020/2021 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

## Data features



| Features                        |            Description             |                       Descrizione                       |
| ------------------------------- | :--------------------------------: | :-----------------------------------------------------: |
| `season`                        |                                    |                                                         |
| `league`                        |                                    |                                                         |
| `matchweek`                     |                                    |                                                         |
| `weekday`                       |                                    |                        Giornata                         |
| `day`                           |                                    |                                                         |
| `month`                         |                                    |                                                         |
| `year`                          |                                    |                                                         |
| `hour`                          |                                    |                                                         |
| `stadium`                       |                                    |                                                         |
| `attendance`                    |                                    |                       Spettatori                        |
| `referee`                       |                                    |                         Arbitro                         |
| `referee_var`                   |            Referree Var            |                       Arbitro Var                       |
| `home_team`                     |                                    |                                                         |
| `away_team`                     |                                    |                                                         |
| `home_team_score`               |                                    |                                                         |
| `away_team_score`               |                                    |                                                         |
| `home_team_score_time`          |                                    |                                                         |
| `away_team_score_time`          |                                    |                                                         |
| `home_team_penalty`             |              Penalty               |                         Rigori                          |
| `away_team_penalty`             |              Penalty               |                         Rigori                          |
| `home_team_penalty_time`        |              Penalty               |                         Rigori                          |
| `away_team_penalty_time`        |              Penalty               |                         Rigori                          |
| `home_team_penalty_scored`      |           Penalty scored           |                     Rigori segnati                      |
| `away_team_penalty_scored`      |           Penalty scored           |                     Rigori segnati                      |
| `home_team_penalty_scored_time` |           Penalty scored           |                     Rigori segnati                      |
| `away_team_penalty_scored_time` |           Penalty scored           |                     Rigori segnati                      |
| `home_team_penalty_missed`      |           Penalty missed           |                    Ricori sbagliati                     |
| `away_team_penalty_missed`      |           Penalty missed           |                    Ricori sbagliati                     |
| `home_team_penalty_missed_time` |           Penalty missed           |                    Ricori sbagliati                     |
| `away_team_penalty_missed_time` |           Penalty missed           |                    Ricori sbagliati                     |
| `home_team_possession`          |             Possession             |                     Possesso palla                      |
| `away_team_possession`          |             Possession             |                     Possesso palla                      |
| `home_team_yellow_card`         |            Yellow card             |                    Cartellini gialli                    |
| `away_team_yellow_card`         |            Yellow card             |                    Cartellini gialli                    |
| `home_team_yellow_card_time`    |            Yellow card             |                    Cartellini gialli                    |
| `away_team_yellow_card_time`    |            Yellow card             |                    Cartellini gialli                    |
| `home_team_red_card`            |              Red card              |                    Cartellini rossi                     |
| `away_team_red_card`            |              Red card              |                    Cartellini rossi                     |
| `home_team_red_card_time`       |              Red card              |                    Cartellini rossi                     |
| `away_team_red_card_time`       |              Red card              |                    Cartellini rossi                     |
| `home_team_fouls_committed`     |          Fouls committed           |                     Falli commessi                      |
| `away_team_fouls_committed`     |          Fouls committed           |                     Falli commessi                      |
| `home_team_fouls_won`           |             Fouls won              |                     Falli ricevuti                      |
| `away_team_fouls_won`           |             Fouls won              |                     Falli ricevuti                      |
| `home_team_shots`               |               Shots                |                          Tiri                           |
| `away_team_shots`               |               Shots                |                          Tiri                           |
| `home_team_shots_onTarget`      |          Shots on target           |                      Tiri in porta                      |
| `away_team_shots_onTarget`      |          Shots on target           |                      Tiri in porta                      |
| `home_team_shots_offTarget`     |          Shots off target          |                       Tifi fuori                        |
| `away_team_shots_offTarget`     |          Shots off target          |                       Tifi fuori                        |
| `home_team_shots_blocked`       |           Shots blocked            |                       Tiri parati                       |
| `away_team_shots_blocked`       |           Shots blocked            |                       Tiri parati                       |
| `home_team_corners`             |              Corners               |                     Calci d'angolo                      |
| `away_team_corners`             |              Corners               |                     Calci d'angolo                      |
| `home_team_offsides`            |              Offside               |                       Fuorigioco                        |
| `away_team_offsides`            |              Offside               |                       Fuorigioco                        |
| `home_team_ownGoals`            |              Own Goal              |                        Autoreti                         |
| `home_team_ownGoals_time`       |              Own Goal              |                        Autoreti                         |
| `away_team_ownGoals`            |              Own Goal              |                        Autoreti                         |
| `away_team_ownGoals_time`       |              Own Goal              |                        Autoreti                         |
| `total_score`                   |            Total score             |                      Totale goals                       |
| `total_penalty`                 |           Total penalty            |                 Totale rigori assegnati                 |
| `total_penalty_scored`          |        Total penalty scored        |                  Totale rigori segnati                  |
| `total_penalty_missed`          |        Total penalty missed        |                  Totale rigori mancati                  |
| `total_ownGoals`                |          Total own goals           |                     Totale autoreti                     |
| `total_yellow_card`             |        Totale yellow cards         |               Totale cartellini    gialli               |
| `total_red_card`                |          Total red cards           |                 Totale cartellini rossi                 |
| `total_fouls_committed`         |        Total foul commited         |                  Totale falli commessi                  |
| `total_shots`                   |            Total shots             |                       Totale tiri                       |
| `total_shots_onTarget`          |       Total shots on target        |                  Totale tiri in porta                   |
| `total_shots_offTarget`         |       Total shots off target       |                    Totale tiri fuori                    |
| `total_shots_blocked`           |        Totale shots blocked        |                   Totale tiri parati                    |
| `total_corner`                  |           Total corners            |                  Totale calci d'angolo                  |
| `total_offsides`                |           Total offside            |                    Total fuorigioco                     |
| `match_final`                   | Final results: 'victory' or 'draw' |             Finale: 'vittoria', 'pareggio'              |
| `team_won`                      |              Team won              |                   Squadra vincitrice                    |
| `team_lost`                     |             Team lost              |                    Squadra perdente                     |
| `team_win_home`                 | 1 if  home team  won, 0 otherwise  |   1 se la squadra di casa è vincitrice, 0 altrimenti    |
| `team_win_away`                 | 1 if  away team  won, 0 otherwise  | 1 se la squadra in trasferta è vincitrice, 0 altrimenti |

