
# Transformando Imagens em Insights

Bem-vindo ao repositório dedicado ao projeto "Reconhecimento Facial e Transformação de Imagens em Dados" utilizando Azure Machine Learning. Este guia passo a passo fornece uma jornada prática e detalhada, capacitando você a explorar e implementar soluções avançadas de reconhecimento facial, enquanto converte eficientemente imagens em valiosos insights e dados utilizáveis.

## Criando Recurso

1. Primeiro passo é abrir o portal do azure: https://portal.azure.com/#home
- Criar um novo recurso
- Passo a passo:
    - Categorias
    - Inteligencia Artificial e Machine Learning
    - Procurar por Azure AI Services (Serviços Cognitivos) e clicar em criar
    - Usar sua assinatura azure
    - Em grupo de recursos caso não tenha, crie um
    - Selecione a região e coloque um nome de sua preferência
    - Em tipo de preço selecione Standard S0 e marque a caixinha
    - Após isso clique em examinar + criar

2. Agora devemos acessar o portal de visão: https://portal.vision.cognitive.azure.com/gallery/featured

- Passo a passo:
    - Ver todos os recursos
    - Selecione o recurso que criamos anteriormente e clique em definir como padrão
    - Apos isso retornamos a pagina anterior 
    - Vamos testar o reconhecimento de faces:
        - Primeiro clicar na aba rosto
        - Detecção de rostos em imagem
        - Marcar a caixinha
        - Você pode testar as imagens do proprio Azure ou enviar outras de sua preferência
    - Agora vamos testar o reconhecimento de caracteres:
        - Clicar na aba Reconhecimento Óptico de caracteres
        - Marcar a caixinha
        - Seguir os mesmos passos anteriores, poderá usar as imagens da propria Azure ou enviar alguma de sua preferência
    - Proximo teste, Análise de Imagens:
        - Clicar na aba ánalise de imagens
        - Adicionar legendas às imagens
        - Marcar a caixinha
        - Usar as imagens da propria Azure ou enviar alguma de sua preferência

## Minha parte pratica neste projeto:
- Na pasta [inputs](https://github.com/lucslima96/transformando_imagens_em_insights/tree/main/inputs) deste projeto deixarei as imagens que utilizei pra teste, retirei de um banco de dados gratuito na internet.
- Na pasta outputs deixarei os resultados de reconhecimento de texto dessas imagens



