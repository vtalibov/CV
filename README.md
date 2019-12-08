CV in LaTex, using [res.cls](https://ctan.org/pkg/res).
If you want it to work wit BibTeX, line 203 in res.cls have to be commented out:

```
\nofiles % resume's don't need .aux files
```
