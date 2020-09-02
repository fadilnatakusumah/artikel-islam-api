### API [KonsultasiSyariah.com](https://konsultasisyariah.com/)
<br>

`GET ALL ARTICLES`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ks
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/ks)
<br>
<br>


`GET ALL ARTICLES WITH PARAMS`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ks
```
```
{
    s: "Tata cara sholat", // "s" for searching query
    page: 1, // "page" for searching on what page
}
```
_example_: [LIST OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/ks)
<br>
<br>

`GET DETAIL ARTICLE`
```
https://artikel-islam.netlify.app/.netlify/functions/api/ks/detail/:id_article
```
_example_: [DETAIL OF ARTICLES](https://artikel-islam.netlify.app/.netlify/functions/api/ks/detail/aHR0cHM6Ly9rb25zdWx0YXNpc3lhcmlhaC5jb20vMzY0NzktdGVybnlhdGEtcHVhc2EtZGktYnVsYW4tc3l1cm8tYWRhbGFoLXB1YXNhLXBhbGluZy1hZmRvbC1zZXRlbGFoLXB1YXNhLXJhbWFkaGFuLmh0bWw=)
