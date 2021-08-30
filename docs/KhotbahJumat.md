### API [Khotbahjumat.com](https://khotbahjumat.com/)
<br>

`GET ALL ARTICLES`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/kj
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/kj)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/kj
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/kj?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/kj/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/fir/detail/aHR0cHM6Ly9raG90YmFoanVtYXQuY29tLzU4OTAtdGFrdXQta2VwYWRhLWFsbGFoLWFkYWxhaC1rZWJ1dHVoYW4taGlkdXAtbWFudXNpYS5odG1s)
