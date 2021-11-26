**Enlaces de referencia:**
- https://www.w3schools.com/tags/att_td_colspan.asp
- https://www.w3schools.com/tags/att_td_rowspan.asp

En el proyecto web en el cual estamos tabajando se han de generar las siguientes tablas:

![Texto alternativo](https://github.com/dannylarrea/table-form/blob/main/tables.png)

Utilizar los siguientes estilos:

```CSS
<style>
    table {
        font-family: Arial, Helvetica, sans-serif;
        border-collapse: collapse;
        width: 100%;
    }

    table td,
    table th {
        border: 1px solid #ddd;
        padding: 8px;
    }

    table tr:nth-child(even) {
        background-color: #f2f2f2;
    }

    table tr:hover {
        background-color: #ddd;
    }

    table th {
        padding-top: 12px;
        padding-bottom: 12px;
        text-align: left;
        background-color: #0000ff46;
        color: white;
    }
</style>
```

Para el alargamiento de celda (en horizontal o vertical) se han de mirar los enlaces de referencia que están al comienzo de esta página.
