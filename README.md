# Your Story, Unwritten

![Your Story, Unwritten](https://img.shields.io/badge/Engine-Unity-000000?style=for-the-badge&logo=unity)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![IA](https://img.shields.io/badge/Dialogos-Gerados%20por%20IA-blueviolet?style=for-the-badge)

**Cada escolha escreve uma nova página. Cada partida conta uma história que nunca foi contada antes.**

*Your Story, Unwritten* é uma visual novel experimental que quebra a quarta parede do design narrativo. Ao aproveitar o poder de modelos modernos de IA, ele gera diálogos e ramificações da história únicos e dinâmicos em tempo real, garantindo que nenhum dois jogadores terão exatamente a mesma experiência.

## ✨ O Conceito Único

Visual novels tradicionais são pré-escritas. **Esta não é.**

A premissa central de *Your Story, Unwritten* é a possibilidade infinita da narrativa. As escolhas que você faz não apenas selecionam uma resposta pré-determinada; elas guiam um contador de histórias de IA que molda as personalidades das personagens, suas reações e a direção do enredo instantaneamente.

Isso significa:
*   **Partidas Verdadeiramente Únicas:** Jogue novamente e encontre conversas, relacionamentos e finais completamente diferentes.
*   **Agência Profunda da Personagem:** Suas escolhas moldam fundamentalmente quem as personagens são e como elas veem o mundo e você.
*   **Um Enredo em Evolução:** Experimente uma história que parece viva e responsiva, cheia de surpresas até mesmo para os desenvolvedores.

## 🎮 Como Funciona & Jogabilidade

1.  **A Fundação:** O jogo prepara o palco com uma premissa central, personagens estabelecidas e arte chave (cenários, sprites, CGs).
2.  **Suas Escolhas:** Você é apresentado a escolhas significativas que vão além de simples opções de diálogo. Você pode escolher a motivação central de uma personagem, o tom de uma interação ou uma grande decisão de enredo.
3.  **Narração por IA:** Com base na sua entrada e no contexto da história em andamento, um sofisticado modelo de linguagem de IA gera o diálogo e o texto de narração dinamicamente.
4.  **Um Mundo Vivo:** As personagens se lembram de interações passadas. Seus diálogos gerados refletem seu relacionamento em evolução com você e o estado mutável do mundo.

**Gênero:** Visual Novel Experimental, Simulação, Ficção Interativa

## 🛠️ Arquitetura Técnica

*   **Engine:** Unity
*   **Componentes Principais:**
    *   **Gerenciador de Contexto Narrativo:** Mantém o estado da história, personagens e mundo para fornecer contexto relevante para a IA.
    *   **Manipulador de API:** Gerencia de forma segura a comunicação entre o jogo e o serviço de IA.
    *   **Sistema de Diálogo:** Um sistema de UI flexível que pode exibir texto e escolhas gerados dinamicamente.
    *   **Sistema de Memória:** Um banco de dados leve (ex: JSON, SQLite) para rastrear flags de história, relacionamentos entre personagens e eventos passados, garantindo consistência narrativa.

## 🎨 Arte & Estilo

*   **Estilo de Arte:** Anime
*   **Assets:** O jogo contará com:
    *   Sprites e expressões de personagens originais
    *   Arte de cenário original
    *   Elementos de GUI/UI personalizados
    *   Trilha sonora e efeitos sonoros originais

*A arte estática fornece a identidade visual bonita e consistente, enquanto a IA fornece o conteúdo textual infinito dentro dessa estrutura.*

## 🎯 Público-Alvo

*   Fãs de visual novels em busca de uma experiência verdadeiramente única e não linear.
*   Jogadores curiosos sobre a interseção entre IA e narrativa.
*   Jogadores que apreciam games com alta rejogabilidade e experiências de "narrativa emergente".

## ❓ Perguntas Frequentes (FAQ)

**P: Isso significa que a história não tem direção e é completamente aleatória?**
**R:** Não. O jogo fornece uma premissa foundational sólida, objetivos claros e personagens bem definidas. A IA opera dentro desses limites para gerar conteúdo coerente e relevante, guiada pelas escolhas do jogador. Pense nisso como um ator de improviso que é especialista no mundo que você criou.

**P: Isso vai exigir conexão com a internet?**
**R:** Sim, para a maioria dos modelos de IA baseados em nuvem. Uma implementação usando um modelo menor executado localmente é uma **possibilidade** para uma versão **futura**, mas tem requisitos de hardware mais altos.

**P: Como vocês previnem a IA de gerar texto quebrado, fora do tópico ou inconsistente?**
**R:** Este é o principal desafio de design. Usamos uma combinação de "prompt engineering" cuidadoso, um sistema robusto de contexto narrativo que alimenta a IA com informações relevantes e filtragem de saída para manter a qualidade e a consistência.

## 🔮 Roadmap Futuro

*   Expansão de arcos de história e novas personagens.
*   Suporte para "fundações de história" criadas pela comunidade (premissas, personagens, arte).
*   Melhor fine-tuning da IA para narrativas mais específicas de gênero (ex: mistério, romance, horror).
*   Versão mobile.

## 👥 Equipe

**Desenvolvido por:** Ryuto
Sim esse é um projeto solitario, por **enquanto**


## 📄 Licença

Este projeto está atualmente sob uma licença proprietária. Todos os assets são copyright de seus respectivos criadores.

---

*A história nunca é a mesma. A escolha é sempre sua.*
