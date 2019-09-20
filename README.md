# rugbywc2019-json
Simple JSON of fixtures for the 2019 Rugby World Cup in Japan

Scores and later fixtures will be updated as the games commence!


All data courtesy of https://www.rugbyworldcup.com/matches

Data structure is as such:

```
{
  'date(str)': {
    'group / event name': [
      {
        'team 1': 'country name',
        'team 2': 'country name',
        'local_time': 'time in JST (str)',
        'uk_time': 'time in GMT (str)',
        'score_team_1': 'final score team 1',*
        'score_team_2': 'final score team 2',*
        'winner': 'winning country',*
        'tie': (bool - true if game resulted in a tie),*
      }
    ]
  }
}
```
`* - denotes that this will be null until data is backfilled`
