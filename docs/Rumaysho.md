### API [Rumaysho.com](https://rumaysho.com/)
<br>

`GET ALL ARTICLES`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/rum
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/rum)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/rum
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/rum?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/rum/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/ks/detail/aHR0cHM6Ly9ydW1heXNoby5jb20vMjkzNzgtamFuZ2FuLWx1cGEtdWNhcGthbi10ZXJpbWEta2FzaWgtZGl0YW1iYWgtZGVuZ2FuLWRvYS5odG1s)
