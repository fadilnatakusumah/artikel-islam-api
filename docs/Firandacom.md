### API [Firanda.com](https://firanda.com/)
<br>

`GET ALL ARTICLES`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/fir
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/fir)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/fir
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/fir?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/fir/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/fir/detail/aHR0cHM6Ly9maXJhbmRhLmNvbS85NTk4LWphZHdhbC1zaWFyYW4tdWYtbGl2ZS0yNC1kaS15b3V0dWJlLWFndXN0dXMtMjAyMS0yLmh0bWw=)
