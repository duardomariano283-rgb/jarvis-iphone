# JARVIS para iPhone — protótipo gratuito

## O que esta primeira versão faz
- Interface futurista adaptada para celular.
- Respostas faladas usando a voz disponível no iPhone.
- Reconhecimento de voz quando o navegador oferece suporte.
- Comandos locais: hora, data, saudações, ajuda e apresentação.
- Campo de texto como alternativa ao microfone.

## Como publicar gratuitamente pelo iPhone
1. Crie uma conta no GitHub (se ainda não tiver).
2. Crie um repositório público chamado `jarvis-iphone`.
3. Envie os três arquivos deste projeto (`index.html`, `manifest.webmanifest`, `sw.js`) para a raiz do repositório.
4. No repositório, abra **Settings > Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e salve.
6. Aguarde a publicação e abra o endereço `https://SEU-USUARIO.github.io/jarvis-iphone/` no Safari.
7. No Safari, toque em **Compartilhar > Adicionar à Tela de Início**.

## Observações importantes
- O microfone exige uma página servida por HTTPS e permissão do usuário.
- O suporte a reconhecimento de voz varia conforme a versão do iOS e o navegador. Se não funcionar, use o campo de texto.
- A fala usa as vozes instaladas/disponíveis no iPhone; a seleção exata de uma voz masculina pode variar.
- Esta versão ainda não usa uma IA generativa: os comandos e respostas são locais e limitados.
- Não coloque chaves secretas de APIs dentro do JavaScript publicado. Uma integração com IA precisa de um serviço intermediário seguro e pode ter limites ou custos.
