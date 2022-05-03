# floating-button
CSS para criar botões flutuantes de redes socias



# Com um único botão

```html
<div class="floating-container">
    <a href="https://google.com" target="_blank">
        <div class="floating-button"><i class="bi bi-whatsapp"></i></div>
    </a>
</div>
```



# Com vários botões

```html
<div class="floating-container">
    <div class="floating-button"><i class="bi bi-chat-dots"></i></div>
    <div class="element-container">
        <a href="https://google.com" target="_blank">
            <span class="float-element">
                <i class="bi bi-whatsapp"></i>
            </span>
        </a>
        <a href="https://google.com" target="_blank">
            <span class="float-element">
                <i class="bi bi-facebook"></i>
            </span>
        </a>
        <a href="https://google.com" target="_blank">
            <span class="float-element">
                <i class="bi bi-instagram"></i>
            </span>
        </a>
    </div>
</div>
```


## Configuração

```html
<head>
    ....

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devisaah/floating-button@main/style.css">

</head>
<body>
    ...
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

</body>

```