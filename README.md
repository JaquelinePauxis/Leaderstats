🏆 Aula 05: Placar (Leaderstats) e Moedas
O sistema de economia do jogo.

📦 Conteúdo para o Repositório: [AULA 05] Placar e Moedas

📄 Arquivos: Você precisará de 2 arquivos aqui: Leaderstats.lua e ColetarMoeda.lua.

📝 Texto para o README.md:

# 🏆 Aula 05 - Placar e Coleta de Itens

## 📖 Sobre o Projeto
Nesta aula, criamos o sistema de economia do jogo. Aprendemos sobre a pasta especial `leaderstats` (que mostra o placar no canto da tela) e como criar objetos interativos (moedas) que aumentam a pontuação do jogador.

## 📂 Como Instalar

### Passo 1: O Placar (Leaderstats)
1. No Roblox Studio, vá até **ServerScriptService**.
2. Crie um **Script** e renomeie para `LeaderstatsScript`.
3. Cole o código do arquivo `Leaderstats.lua`.

### Passo 2: A Moeda
1. Crie uma **Part** (ou Cilindro) amarela no Workspace.
2. Certifique-se de que ela está **Anchored** (Ancorada).
3. Dentro dessa peça, crie um **Script**.
4. Cole o código do arquivo `ColetarMoeda.lua`.

⚠️ Dicas de Debug (Erros Comuns)
O placar não aparece: Verifique se escreveu leaderstats tudo minúsculo no Script 1.

Erro "Dinheiro is not a valid member": Verifique se o .Name do dinheiro é igual nos dois scripts (Maiúsculas importam!).

A moeda cai no infinito: Lembre-se de marcar a propriedade Anchored na moeda.
