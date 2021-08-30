### API [Muslimafiyah.com](https://muslimafiyah.com/)
<br>

`GET ALL ARTICLES`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/maf
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/maf)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/maf
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH SEARCH PARAM](https://artikel-islam.netlify.app/.netlify/functions/api/maf?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
GET - https://artikel-islam.netlify.app/.netlify/functions/api/maf/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/ks/detail/aHR0cHM6Ly9tdXNsaW1hZml5YWguY29tL3dhaGFpLWF5YWh0aWRhay10YWh1LWphbGFuLW1lbnVqdS1zdXJnYS1idWthbmthaC1lbmdrYXUtbmFoa29kYW55YS5odG1s)
