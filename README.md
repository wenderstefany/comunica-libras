# Comunica Libras

Protótipo web de apoio à comunicação entre colaboradores surdos e ouvintes.

## Publicação
Este projeto é um site estático e pode ser publicado em GitHub Pages, Netlify, Vercel ou outro serviço de hospedagem estática.

O arquivo principal é `index.html`.

## Recursos atuais
- Português -> Libras via VLibras
- Entrada por voz -> texto (navegadores compatíveis)
- Câmera para preparar o módulo Libras -> Português
- Campo de mensagem ampliada
- Frases rápidas para comunicação

## Observação
O reconhecimento automático de Libras pela câmera ainda não está implementado. Essa etapa requer um modelo de visão computacional treinado/validado para Libras e uma camada de interpretação dos sinais.

## Privacidade
A câmera só é solicitada quando o usuário clica em "Ativar câmera". O projeto não contém servidor próprio nem banco de dados.
