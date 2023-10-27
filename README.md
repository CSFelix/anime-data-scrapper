<h1 align="center" id='api-consumer-scrapper' style='color:#7159c1'>⛏️ API Consumer: Scrapper ⛏️</h1>
<p align="center"><i>Getting animes, users and scores data from MyAnimeList with Jikan</i></p>

<br />

```
- Animes Data Fetcher
- Users Data Fetcher
- Users Details Fetcher
- Users Scores Fetcher
- Filtering Datasets
```

<br />

All the datas are extracted from [MyAnimeList (MAL)](https://myanimelist.net) website via its unofficial API [Jikan](https://jikan.moe). Jikan contains some limitations about the amount of requisition per time, so you can use this API Consumer in two ways: 1) getting only data from id 0 to 100; 2) getting all available data. This last one takes several time, so patience 😅

The table below shows the requisitions limitations per time:

<table style='border-style: solid'>
    <caption>Jikan API Requisitions per Time</caption>
    <tr align='center' style='border-style: solid'>
        <th style='border-style: solid'>Duration</th>
        <th style='border-style: solid'>Requests</th>
    </tr>
    <tr align='center'>
        <td style='border-style: solid'>Daily</td>
        <td style='border-style: solid'><b>Unlimited</b></td>
    </tr>
    <tr align='center'>
        <td style='border-style: solid'>Per Minute</td>
        <td style='border-style: solid'>60 requests</td>
    </tr>
    <tr align='center'>
        <td style='border-style: solid'>Per second</td>
        <td style='border-style: solid'>3 requests</td>
    </tr>
</table>

<br />

You can check its documentation here: [Jikan Documentation](https://docs.api.jikan.moe/#section/Information).

---

⚙️ Environment

- Python 3.10.x Version;
- Jupyter Lab 3.5.x Version;
- BeautifulSoup, JSON, Numpy, Pandas, Re, Requests and Time Packages

```bash
pip install bs4 json numpy pandas re requests time
```
