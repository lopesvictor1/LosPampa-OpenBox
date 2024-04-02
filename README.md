<h1 align="center">
  <br>
  <img src="./images/lospampa_card.png" width="600"></a>
  <br>
  PampaBox
  <br>
</h1>
<h4 align="center">O projeto PampaBox visa transformar dispositivos TV Box em computadores educacionais. 

## Visão Geral

O objetivo principal do PampaBox é transformar TVs comuns em ferramentas educacionais poderosas, proporcionando acesso à internet, conteúdo educacional e capacidade de processamento avançada através da instalação de sistemas operacionais baseados em Linux. Além disso, o projeto busca criar clusters de processamento utilizando esses dispositivos reutilizados, para fornecer alta capacidade de processamento com baixo custo.



## Recursos Principais

- Instalação de sistemas operacionais baseados em Linux para utilização em ambientes escolares.
- Criação de clusters de processamento utilizando dispositivos TV Box reutilizados.
- Promoção da sustentabilidade através da reutilização de dispositivos eletrônicos.
- Fornecimento de acesso à internet e conteúdo educacional em comunidades de baixa renda.



## Como Contribuir

Você pode contribuir para o PampaBox de várias maneiras:

1. **Desenvolvimento:** Ajude no desenvolvimento de novos recursos, melhorias de desempenho e correção de bugs.
2. **Testes:** Teste o software em diferentes dispositivos e ambientes para identificar problemas e relatar bugs.
3. **Documentação:** Contribua para a documentação do projeto, tornando-o mais acessível para novos usuários e colaboradores.
4. **Divulgação:** Compartilhe o projeto com sua rede para aumentar sua visibilidade e impacto.



## Como Começar

Para começar a utilizar o PampaBox em sua escola ou comunidade, siga estas etapas:

1. Consulte a seção de [Requisitos](#requisitos) para garantir que seu hardware seja compatível.
2. Siga as instruções de [Instalação](#instalação) para configurar o sistema operacional baseado em Linux nos dispositivos TV Box.
3. Explore os recursos e funcionalidades disponíveis para começar a utilizar o PampaBox em seu ambiente educacional.
4. Contribua para o projeto e compartilhe sua experiência com a comunidade!



## Requisitos

- Conexão com a internet.
- Televisão com entrada HDMI.
- Dispositivos TV Box:
- Um SD Card (cartão de memmória) de pelo menos 8GB
- Realize um backup da ROM atual da sua TVBox em caso de falhas durante o processo de instalação (Opcional, mas recomendado).


## Instalação


- Verifique se o seu modelo de TVBox já possui um guia de instalação disponível. Caso seu dispositivo esteja listado, clique na aba "Link":

| Modelo da Placa    | SoC | Processador     | Mem     | HD | Instalação |
|------------|------|-----------------|:-------:|:-------------:|:------------------------------------------------------------------------:|
| Amlogic p281 | S905W |Quad-core ARM Cortex-A53 - 1200Mhz  | 1GB     | 8GB   |[Link](https://github.com/lopesvictor1/PampaBox/tree/main/boxes/amlogic-p281.md)     |
| Amlogic p212 | S905X   | Quad-core ARM Cortex-A53 1000Mhz | 1GB     | 8GB          |[Link](https://github.com/lopesvictor1/PampaBox/tree/main/boxes/amlogic-p212.md)     |
| Amlogic Q201        | S912 | Octa-core ARM Cortex-A53 - 1200Mhz | 2GB     | 16GB           |[Link](https://github.com/lopesvictor1/PampaBox/tree/main/boxes/amlogic-q201.md)    |
|Allwinner dolphin| H3 (sun8iw7p1)| Quad-core ARM Cortex-A7 1000Mhz |X GB| X GB| [Link](https://github.com/lopesvictor1/PampaBox/tree/main/boxes/allwinner-dolphin.md) |



Caso possua dúvidas de como descobrir o modelo da placa ou SoC de sua TVBox siga nosso [Guia](./boxes/verificar-modelo-placa.md). 


## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).