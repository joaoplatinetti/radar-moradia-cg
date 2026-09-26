# Radar de moradia · Campo Grande - MS

Os 74 bairros oficiais de Campo Grande, lado a lado.

**→ [Ver a página](https://joaoplatinetti.github.io/radar-moradia-cg/)**
· [painel de mercado](https://joaoplatinetti.github.io/radar-moradia-cg/mercado.html)

Este repositório guarda **apenas a página publicada**, regerada todo dia. O código,
os dados e o método vivem em outro lugar.

## O que a página mostra

Para cada bairro: quantos imóveis estão anunciados, há quanto tempo o anúncio mediano
está no ar — que é a medida de quanta margem há para negociar, e que nenhum portal
publica —, cobertura de esgoto, escolas e unidades de saúde, distância ao Centro e ao
terminal mais próximo, região urbana, e o que o Censo 2010 registra de renda e de
domicílios alugados.

## O que ela ainda não mostra

**Preço por bairro.** A página de anúncio do portal não abre para acesso automatizado,
então preço sai por amostragem em navegador, algumas dezenas de imóveis a cada dois
dias. Um bairro só recebe mediana quando a amostra dele chega a 15 imóveis. Enquanto
não chega, o espaço fica vazio e a página diz por quê — três medianas de três anúncios
enganariam com mais confiança do que a ausência.

## Limites, ditos e não escondidos

1. **Preço pedido não é preço fechado.** Quando chegar, será o que se pede no anúncio.
2. **Renda e taxa de aluguel são de 2010** — os únicos anos em que o IBGE publica os dois
   por bairro. Servem para ordenar bairros, não para dizer valores de hoje.
3. **Distância é em linha reta.** Quem mora do outro lado do córrego anda mais.
4. **Escola e saúde vêm do OpenStreetMap**, que é colaborativo: onde ninguém mapeou, a
   contagem sai menor que a realidade.
5. **Anúncio repetido entre imobiliárias infla o estoque.** O viés é de nível e não de
   tendência, então comparar bairros continua de pé.

## Fontes

Estoque de anúncios: [InfoImóveis](https://www.infoimoveis.com.br) (sitemap público).
Bairros, domicílios e infraestrutura: IBGE, Censos 2022 e 2010. Regiões urbanas:
PLANURB / Prefeitura de Campo Grande. Escolas, saúde e terminais:
[OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL).

Os dados pertencem às suas fontes e seguem os termos de cada uma.
