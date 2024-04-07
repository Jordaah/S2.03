# Compilation de Markdown en PDF et HTML

## PDF:
```sh
pandoc -s -N --toc --metadata title="Sommaire" rapport.md -o rapport.pdf
```

##  HTML

```sh
pandoc -s -N --toc --metadata title="Sommaire" rapport.md -o rapport.html
```