# Android Crypto Monitor 📱🚀
Projeto de monitoramento de criptomoedas. Build rápido, direto e funcional.

📂 Estrutura do Código

Arquivo | Função
MainActivity.kt | Ponto de entrada. Gerencia a tela principal e atualizações de UI.
CryptoService.kt | Conecta na API de dados de cripto (coin market) e puxa as informações.
CryptoFactory.kt | Cria instâncias de objetos baseados nos dados recebidos da API.
CryptoModel.kt | Representa as criptomoedas (nome, preço, variação). Puro dados.
