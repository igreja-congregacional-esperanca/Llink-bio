# Link da bio · IEC Esperança

Página de link da bio da Igreja Evangélica Congregacional Conjunto Esperança, com três capas: Site, YouTube e Localização.

## Como editar os links

Abra o `index.html`, procure por `LINKS` perto do final do arquivo e troque os endereços:

```js
var LINKS = {
  site: "https://www.iecesperanca.com.br/",
  youtube: "https://www.youtube.com/@IECConjuntoEsperan%C3%A7a",
  local: "https://share.google/pRhKdVoDIfqXM68cA"
};
```

Se um endereço ficar vazio, o botão correspondente fica sem destino.
