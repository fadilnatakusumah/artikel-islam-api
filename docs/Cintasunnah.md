### API [CintaSunnah.com](https://cintasunnah.com/)
<br>

`GET ALL ARTICLES`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/cs
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/cs)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/cs
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/cs?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/cs/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/cs/detail/aHR0cHM6Ly9jaW50YXN1bm5haC5jb20vZGlhbnRhcmEta2FpZGFoLWthaWRhaC1zZXB1dGFyLWphaGFsYWgv)
