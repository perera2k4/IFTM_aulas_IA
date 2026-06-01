## Interpretar os resultados em linguagem acessível ao gestor

Os resultados são refletidos por três indicadores principais que o algoritmo apriori apresenta sobre o comportamento da compra dos clientes:

- **Suporte:** Mostra a frequência com que os itens aparecem nas compras. Produtos como pão e leite são os mais comprados, aparecendo em mais de 60% das compras realizadas.
- **Confiança:** Indica maior potencial de um cliente levar um produto "B" já que colocou o produto "A" no carrinho.
- **Lift:** É a métrica mais importante para o supermercado, pois mostra o quanto a compra de um item _impulsiona_ a venda do outro, reduzindo o fator sorte. Um Lift acima de 1 significa que os itens têm uma conexão real e forte.

### Principais padrões apresentados

| Combinação de Produtos                         | Nível de Confiança | Força do Impulso (Lift)          |
| :--------------------------------------------- | :----------------- | :------------------------------- |
| **Pão + Café** impulsionam **Açúcar + Leite**  | 93,3%              | 3.95 (Quase 4x mais ocorrências) |
| **Açúcar + Pão** impulsionam **Leite + Café**  | 94,1%              | 3.95 (Quase 4x mais ocorrências) |
| **Leite + Feijão** impulsionam **Arroz + Pão** | 97,2%              | 2.95 (Quase 3x mais ocorrências) |
| **Manteiga** impulsiona **Pão**                | 97,9%              | 1.54 (Associação direta e forte) |

## Propor ações práticas baseadas nas regras encontradas

Com base nas regras de associação mais fortes encontradas na base de dados, pode-se apresentar algumas estratégias para o supermercado:

### O conjuto para o café da manhã (Pão, Café, Açúcar e Leite)

Os dados mostram que esses quatro itens têm a maior associação do supermercado, com um Lift de 3.95. Eles são comprados juntos em praticamente todas as combinações possíveis.

- **Gôndola:** Crie um ponto de venda cruzada. Coloque uma tela ou cesta com pacotes de café e açúcar refinado imediatamente ao lado da seção de panificação ou em frente ao leite.
- **Preço:** Como a confiança dessas regras ultrapassa 93%, colocar o pão em promoção para atrair o cliente para o fundo da loja e manter a margem de lucro cheia no café, leite e açúcar.

### Os principais alimentos consumido pela população (Arroz, Feijão, Leite e Pão)

A regra mostra que clientes que compram leite e feijão em 97% dos casos também levam arroz e pão.

- **Layout:** Embora pertençam a categorias diferentes, garanta que a jornada visual do cliente faça sentido. O corredor de itens básicos como arroz e feijão deve ser um caminho de passagem natural ou obrigatório para quem se dirige à padaria ou ao setor de laticínios.
- **Promocional:** Evite dar descontos simultâneos em arroz, feijão e leite. Como eles puxam a venda uns dos outros, basta colocar um deles em para promover a venda cruzada dos demais a preço cheio.
