### API [Muslimah.or.id](https://muslimah.or.id/)
<br>

`GET ALL ARTICLES`
```
https://artikel-islam.netlify.app/.netlify/functions/api/msh
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/msh)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
https://artikel-islam.netlify.app/.netlify/functions/api/msh
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/msh?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
https://artikel-islam.netlify.app/.netlify/functions/api/msh/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/msh/detail/aHR0cHM6Ly9tdXNsaW1haC5vci5pZC8xMzEwNy1tZW5nZ2FudGktc2hhbGF0LXN1bm5haC1yYXdhdGliLXlhbmctdGVybGV3YXQuaHRtbA==)
