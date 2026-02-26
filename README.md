# 🌌Star Wars(Characters, Planets and Starhips) com API

Um projeto web que consome a SWAPI, Star Wars API, para exibir informações sobre personagens, planetas e naves do universo Star Wars.

Nota: A API original foi descontinuada. Este projeto utiliza uma API alternativa que retorna apenas os dados textuais. Por isso, todas as imagens foram adicionadas manualmente ao projeto.

# 📸Páginas
 
 O projeto é dividido em três seções:
 
 Characters - lista todos os personagens com nome, altura, peso, cor dos olhos e ano de nascimento
 
 Planets - lista os planetas da saga
 
 Starships - lista as naves espaciais
 
 
# ✨Funcionalidades
 
 Consumo de API REST com fetch e async/await
 
 Cards com imagem de fundo de cada personagem/planeta/nave
 
 Paginação com botões Anterior e Próximo, controlados pela resposta da API
 
 Modal de detalhes ao clicar em um card, com informações completas
 
 Imagem padrão (default.jpg) exibida quando não há imagem mapeada para o item
 
 Dados traduzidos para o português (cores dos olhos, unidades de medida, etc.)
 
 
 # 🛠️Tecnologias
 
 HTML5
 
 CSS3
 
 JavaScript (Vanilla)
 
 SWAPI alternativa
 
 Font Awesome(ícones de redes sociais)
 
 # ⚠️Sobre as Imagens
 
 A API utilizada não fornece imagens dos personagens, planetas ou naves. Como solução, as imagens foram mapeadas manualmente no arquivo utils.js, onde cada nome retornado pela API corresponde a um caminho local. Caso um item não tenha imagem mapeada, é exibida uma imagem padrão.
