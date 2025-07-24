# Meus Aprendizados Recriando a Lógica do Carrinho da Shopee com Node.js

Este não é apenas um projeto, é o registro de uma virada de chave. A ideia era simples: recriar a lógica por trás de um carrinho de compras como o da Shopee. O resultado foi muito mais do que um punhado de código que funciona. Foi uma aula prática sobre como pensar e organizar software.

Aqui está o que eu aprendi de verdade.

---

### 🚀 Os Grandes "Ahas!" que Tive no Processo

#### 1. Modularização é Liberdade
Antes, minha tendência seria criar um arquivo gigante e jogar toda a lógica lá dentro. Neste projeto, eu senti na pele o poder de quebrar o problema em pedaços. Criei módulos para:
- **`itens`**: Gerenciar os produtos.
- **`carrinho`**: Cuidar das ações como adicionar, remover e calcular.
- **`utils`**: Funções auxiliares para formatar preços, etc.

**O que eu aprendi:** Código modular não é só "organizado", é mais fácil de testar, de dar manutenção e de entender meses depois. Cada "peça" tem sua responsabilidade, e isso muda o jogo.

#### 2. Traduzindo o Mundo Real para a Lógica
A parte mais desafiadora e gratificante foi transformar regras de negócio reais em funções puras. Como o carrinho deve se comportar quando:
- Um item é adicionado? `(calcula o subtotal)`
- A quantidade de um item muda? `(recalcula tudo)`
- Um item é removido? `(atualiza o total)`

**O que eu aprendi:** Programar não é apenas sobre a sintaxe do Javascript; é sobre modelar o pensamento. Eu tive que sentar e desenhar o fluxo de dados antes de escrever uma única linha de código. Isso me forçou a pensar de forma muito mais estruturada e funcional.

#### 3. Node.js Brilha nos Bastidores
Usar Node.js para essa tarefa foi perfeito. Ele atuou como o "cérebro" central que orquestrava tudo. Toda a lógica de cálculo, adição e remoção rodou no backend, garantindo que as regras de negócio estivessem seguras e centralizadas.

**O que eu aprendi:** Vi na prática como Node.js é poderoso para criar lógicas de aplicação (APIs ou serviços) de forma rápida e eficiente. Ele foi o motor que fez tudo acontecer por trás das cortinas, exatamente como deve ser.

#### 4. Um Projeto Bem Estruturado é Meio Caminho Andado
No final, eu não tinha apenas um código que funcionava, mas sim um **pequeno sistema**. Com uma estrutura de pastas clara e responsabilidades bem definidas, eu sei exatamente onde ir se precisar mudar uma regra de cálculo ou adicionar uma nova funcionalidade (como um cupom de desconto, por exemplo).

**O que eu aprendi:** A organização inicial do projeto define se você terá paz de espírito ou dor de cabeça no futuro. Este projeto me deu um modelo mental para começar projetos maiores com o pé direito.

### ✨ Conclusão

Recriar o carrinho da Shopee desmistificou muito do que eu considerava "complexo". Agora, vejo que grandes sistemas são, na verdade, um conjunto de pequenos sistemas bem feitos e conectados. Levo deste projeto não apenas o conhecimento técnico em Node.js e modularização, mas a confiança para encarar desafios maiores.
