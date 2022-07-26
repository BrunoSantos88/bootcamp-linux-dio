# bootcamp-linux-dio

Começando bootcamp na Dio.Primeiro repositorio!
Esse bootcamp foi desafiador.

Tive que encontrar um meio de usar o EFS para conectar 3 instancias, nao foi facil.
Tive muita dificuldades com banco de Dados , opitei por criar um rds e usar o endpoint.

Minha facilidade foi de usar Python para criar instancia,rds rapidamente.
Criar database e as colunas via python connector, facilitou um pouco.

Quem opitar por fazer por python, so alterar chave e key da aws .
Criar e Python connector , usar endpoint e database e senha do banco de dados, funciona do mesmo jeito.

terminado.

Gostaria de ter emplementado o trafeik como proxy reverso, mais deixa para proxima.

Uma dica caso user EFS da AWS .

sudo mount -t nfs4 IP:/ /var/lib/docker/volumes/app/_data

Boa Sorte!

<img align="center" alt="Rafa-Js" height="980" width="800" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1#R7Vxbc5s4FP41fnQGcbUf40u6nWl3s%2FXOpOlLRgbZ1gYjL8i3%2Fvo9AoEByY3rjUm6JvEk6OjK%2Bc53dCSEO9ZwufsQ49XiMwtI2DGNYNexRh3TRE7PgH9Css8kpoHcTDKPaSBLHQQT%2Bp1Ioaw4X9OAJJWCnLGQ01VV6LMoIj6vyHAcs2212IyF1V5XeE4UwcTHoSp9oAFfZNKe6R3kvxE6X%2BQ9I7ef5SxxXljeSbLAAduWRNa4Yw1jxnh2tdwNSSi0l%2Bslq3d3JLcYWEwifkqFr38sP3%2F9HT0kz9vtrHv%2F5%2F7B4F3ZygaHa3nDtw8TEAxDtg7kuPk%2BV8aK0YinCnUG8IH%2BhkbHgZyhSN2YTk1QT3tVAVJToo2qoJ72qgJUbx7V%2Bkf1AZYESqrSvFHr3ygNED7WgK15SCMyLEzPAOE8xgEFSIYsZDHIIhaB9gYLvgwhheByu6CcTFbYF1rdAm9ANmMRl8aPzDwtFS9aBfPmGPqKZRspEiQeb0gGSFYmDPEqodOiVkz8dZzQDflCkqxxIQVDXInr5W4uSHuDt4l9M4%2FZepUO%2FyP0pc19gssnXxjGEw65aIjH7JnkN9oxLfi9E8Y3mNEwrClgQ2JOgVe3IZ2L9jkT3WGZCsksbRG0QqP5pzQ1sgypCV0XAU4WJJC3pHIhN2zolexKIsmND4QtCY%2F3UGR7oDWyHEnWRYnTniuFWPqSeVH5QDe4kIzTs4%2FunY%2FerZXgjfWX9Wh17x%2BDb13LVOm3wTTEUxpSLgb3TSivTkONdhUokO2NB7dlPaGjINSNrabyoqmSkZoHrSsqrgJx3O2oUMhW%2BpadtVOCxjI8DTL2xZCxWmQ0yORMKAODdJS5HDC2onQSwIwtkyzmCzZnEQ7HB%2BkAvFcUFM7iUOYTE1pO9f834XwvVYjXnFVdNtlR%2FlVUh%2BkgSz3KxsT1aFdO7PNEBPebVXLBeKXgsZx7qJimKjXvSUxBZanHN45CLO79DIBBf2wd%2B%2BQEBnAczwl%2FsaBqMjEJMYe5pxqSvbo99BSifgdou1gxE6ACr6Japabkq4bC%2BSTlkyjFQyHrkgZBami6qb1qfE0xFXmSgUXgrTDX0xDXuhRvTRWn1qGapu1amqnOvpBH1Q5Qw6AvZE4hCGzD%2Fzb8L4X%2FcWYVP2Lg5eJ%2BPcn%2FS9y%2Fq3o86Scd1U8is68LcYyLhTgKH%2B%2FX05D6gozraQSTcUvMlpglYiaiOZhEnw6FJylF84aVdbrd6yG7xleQj%2FuwtnZfcbGe96NZrJ8zl2ZT1alUtnVUtjRUdp1LUdlWqKxwN3km3F9I1WiJrCWzjtBaUqvErhRLqabpoS7UyTxViNRiOTtVoU6mc0X12khTG9VqH3cExzaU6g4C8u683tiwS3kjCtTl6SwIDiQWZlXn0MhwhsjTsW6W%2FtTZkFPtE56S8J4lVDY%2FZZyz5YtcLNYkJUf2ktPCySpTx4zuxDj0nicm2Rox8zvgsxKdByK%2BeSqlj092x3eCqozuaRhtawiNLrb9gFQCN7D9cMJa%2F0eRxItrfefEpT4y9Gg1s9Q3nbfQ%2FRn7Lo1g4b4pFO5bQFHsqBWJdDct25NrYD%2BtEVztt8TVaeOVNl5p45Wz4xW7994CFrdldMvoltHnr0C898Zodbu%2BZfQvxGh75EHmzzEafuxB%2F2oYHWCOpzghl6S1W6W1banP4ZDuAWkhfP01lXcNy9v8tMiL66AjW73NrIPyUbZO9td0sq5xa1nezzlZ0%2FMQcq%2FGyQKPEhjeE2iBPCX7hJPlJRdGnln1t7qHM46r8be58PU5rlsauenBVqH3Ctndf9Ysz%2Bhmj%2BxuoQCoZZcqLc%2BHq7n4%2FzFKOI58ijviZPoS%2FgbMfwa4YUwiK8QByzuDwWf9ZVUVP%2FM%2Bzi1dyjDM2kSMVLsoXiJo5KAS8hSzmJB4QwMm0PsymrxTgM46sXRO5GRaN04FMtdQYycIqJrETF0TlTAb3107ZrZbRczpa7yvLtq93HO0voLYKPeQky2OwWW6eCk0Fk2TVaoaQ7gGiP9WIWg7uXZEzarb1Bxbavh8pxox%2F2XegOAz9WN25WghVEVLdxoXGY3Cpb741cJVvOVQIxfSuctm4TJbuI5HJP13xy71CCcFxexuVovVlYPlWqgWPtqaLXWz0ZDfUoOR9B2S6ZVj5dT8YNdTkWo0yLDVICMFyv8%2FAXXOyVdkmGaNVl3rrcFSQ4yJPKjcEW%2F7i6PKddhOed1nNLIcoYvz3vApajeHTS340%2BxwIMPVIOOe8d4xJA%2FfKJDmlb6YwRr%2FCw%3D%3D" />


<img align="center" alt="Rafa-Js" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" /> +
<img align="center" alt="Rafa-Js" height="50" width="100" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" /> +
<img align="center" alt="Rafa-Js" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" /> +
<img align="center" alt="Rafa-Js" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/putty/putty-original.svg" /> +



