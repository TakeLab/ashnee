# ashnee

**WIP. Additional information and code will be added soon.**

**A**utomatically **S**craped **H**ard **N**ews **E**vent **E**xtraction dataset.

## Statistics

The dataset contains $2279$ articles in total, spread across $26$ hard-news
event types and an additional class *Other*. The table below shows the number of
documents for each event type.

| **Event Type**                    | **#Documents** | **Event Type**              | **#Documents** |
| :-------------------------------- | :------------: | :-------------------------- | :------------: |
| Air crash                         |       55       | Mass Poisoning              |       7        |
| Armed Conflict                    |       76       | Military Exercise           |       70       |
| Bank Robbery                      |       7        | Mine Collapses              |       4        |
| Disease Outbreaks                 |       59       | Mudslides                   |       21       |
| Droughts                          |       18       | Other                       |      1229      |
| Earthquakes                       |       56       | Protest_Online Condemnation |       68       |
| Environment Pollution             |       39       | Regime Change               |       2        |
| Famine                            |       12       | Riot                        |       16       |
| Financial Crisis                  |       27       | Road Crash                  |       86       |
| Fire                              |       77       | Shipwreck                   |       37       |
| Floods                            |       84       | Strike                      |       65       |
| Gas explosion                     |       23       | Train collisions            |       6        |
| Hurricanes_Tornado_Storm_Blizzard |       98       | Tsunamis                    |       0        |
| Insect Disaster                   |       24       | Volcano Eruption            |       13       |

## Data sources

For majority of articles you can find the url in the `ashnee_url.csv` file.

Articles were mainly scraped from the following portals/domains: *dailymail.co.uk*,
*thewest.com.au*, *bbc.com*, **allafrica.com*, *thetimes.co.uk*, *nzherald.co.nz*,
*indiatimes.com*, *sputniknews.com*, *indepedent.co.uk*, *9news.com.au*,
*inquirer.net*, *theguardian.com*, *mb.com.ph*, *punchng.com*, *thestar.com.my*,
*sott.net*, and *news.com.au*.

Most articles were published between 2019. and 2022.

## Models

List of models we fine-tuned for event detection: roberta-base, roberta-large,
deberta-base, deberta-large, distilroberta-base, and albert-base-v2.

List of models we fine-tuned for argument extraction: roberta-base, roberta-large,
deberta-base, deberta-large, distilroberta-base, and albert-base-v2
