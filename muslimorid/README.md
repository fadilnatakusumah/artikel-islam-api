### API [Muslim.or.id](https://muslim.or.id/)
<br>

`GET ALL ARTICLES`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ms
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/ms)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ms
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES WITH PARAMS](https://artikel-islam.netlify.app/.netlify/functions/api/ms?page=1&s=shalat)
<br>
<br>

`GET DETAIL ARTICLE`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ms/detail/:id_article
```
_example_: [DETAIL OF ARTICLE](https://artikel-islam.netlify.app/.netlify/functions/api/ks/detail/aHR0cHM6Ly9tdXNsaW0ub3IuaWQvNjE3ODYtamFuZ2FuLWRla2F0aS1wZXJ1c2FrLWFnYW1hLmh0bWw=)
