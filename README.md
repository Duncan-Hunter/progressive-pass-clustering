# progressive-pass-clustering

Python implementation of [Finding repeatable progressive pass clusters
and application in international football](https://content.iospress.com/articles/journal-of-sports-analytics/jsa220732) using [Statsbomb Open Data](https://github.com/statsbomb/open-data). It's all in a Jupyter notebook because its not for production.

![2015/16 progressive pass clusters](img/team_analysis.png)

#### Installation with poetry:

```bash
poetry install
cp env .env
```

I've exported `requirements.txt` if you prefer using `pip`, but no guarantees are made.

In `.env` set `OPEN_DATA_PATH` to where you have Statsbomb Open Data cloned.
