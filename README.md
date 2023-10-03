# Volvo Cars (Global Online Digital)

## Codificação Front-end (React)

codificação front-end para a Volvo Cars (Global Online Digital). Abaixo está uma descrição do que foi realizado neste projeto:

### Desktop

![ProductListDesktop](./docs/ProductList-Desktop.png)

### Mobile

![ProductListDesktop](./docs/ProductList-Mobile.png)

Busca dos dados necessários para renderizar o design a partir do arquivo public/api/cars.json. Os dados têm a seguinte estrutura:

```json
[
  {
    "id": "xc90-recharge",
    "modelName": "XC90 Recharge",
    "bodyType": "suv",
    "modelType": "plug-in hybrid",
    "imageUrl": "/images/xc90_recharge.jpg"
  }
]
```
Geração de links para as páginas de aprendizado e compra de cada carro, concatenando o id do carro às URLs de aprendizado (`/learn/`) e compra (`/shop/`).

Adição de dois ícones SVG fornecidos pelo designer, armazenados na pasta docs.

Utilização do framework Next.js para a inicialização do projeto.

Garantia de suporte a navegadores modernos e sempre atualizados.

Implementação do design utilizando React e TypeScript para garantir a tipagem segura.

Foco na acessibilidade para melhorar a experiência do usuário.


Utilização da biblioteca de componentes do sistema de design VCC-UI `docs`,  quando aplicável.
Adição de uma barra de filtro na parte superior para filtrar carros por `bodyType`




