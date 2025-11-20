# 💰 MoneyStack

Um aplicativo de **Organização de Finanças Pessoais** que funciona por meio de conversas em linguagem natural.  
A proposta é simplificar o controle financeiro sem formulários manuais ou planilhas complexas, oferecendo uma experiência fluida e integrada ao app do banco do usuário.

---

## 📌 Contexto
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização.  
O **MoneyStack** resolve isso com uma experiência **conversacional**, recomendações automáticas e relatórios simples.

---

## 🎯 Problema
- Entrada manual excessiva nos apps de finanças.  
- Pouca personalização e engajamento.  
- Usuários iniciantes acabam desistindo do controle financeiro.  

---

## 👥 Público-Alvo
- Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação.  
- Principalmente **iniciantes**, que não têm familiaridade com planilhas ou sistemas complexos.  

---

## 🚀 Funcionalidades-Chave
1. Registrar gastos via **chat em linguagem natural**.  
2. **Classificação automática** das transações.  
3. Definir e acompanhar **metas financeiras**.  
4. Receber **dicas de economia** do “Agente Financeiro”.  
5. Visualizar **relatórios simples e personalizados**.  
6. Ser avisado quando ultrapassar o **orçamento mensal**.  
7. Integração fácil com o **app bancário** do usuário.  

---

## 🛠️ MVP (Produto Mínimo Viável)
### Telas principais
- **Chat** (interação com o Agente Financeiro)  
- **Metas e alertas**  
- **Relatórios simples**  

### Recursos necessários
- Processamento de linguagem natural (NLP)  
- Motor de categorização automática  
- Sistema de notificações  
- API de integração bancária  

### Validação inicial
- Testes com grupo piloto de usuários iniciantes  
- Medir engajamento (quantidade de interações no chat)  
- Avaliar clareza dos relatórios e utilidade das dicas  

---

## 📚 Conceitos Importantes

### 🔹 PRD (Product Requirements Document)
- Documento que organiza **o que será feito** e **por que será feito**.  
- Estrutura típica: contexto, problema, público-alvo, funcionalidades-chave e entregáveis.  
- Funciona como um **mapa** que guia o desenvolvimento do produto.  

### 🔹 Vibe Coding
- Abordagem de programação **fluida e criativa**, usada em plataformas como **Lovable**.  
- Em vez de escrever código detalhado, você descreve **a intenção ou comportamento desejado**.  
- O sistema traduz essa descrição em código funcional.  
- É como **codar pela intenção**, não pela linha de código.  

---

## 🎬 Exemplo de Fluxo de Conversa (Storyboard)

**Usuário:** "Gastei R$ 45 ontem com jantar fora."  
**Agente Financeiro:** "Ok, registrei um gasto de R$ 45 na categoria *Alimentação*. Quer definir um limite mensal para restaurantes?"  

**Usuário:** "Sim, coloca R$ 300."  
**Agente Financeiro:** "Meta definida: máximo de R$ 300 em restaurantes por mês. Vou te avisar se você ultrapassar."  

**Usuário:** "Quanto já gastei este mês?"  
**Agente Financeiro:** "Até agora você gastou R$ 120 em restaurantes. Restam R$ 180 do seu orçamento."  

**Usuário:** "Me dá uma dica para economizar."  
**Agente Financeiro:** "Você pode cozinhar em casa 2 vezes por semana. Isso pode reduzir seus gastos em até R$ 100/mês."  

---

## 📈 Roadmap Futuro
- Expansão das integrações bancárias.  
- Relatórios avançados com insights de comportamento financeiro.  
- Recomendações personalizadas de investimentos.  
- Suporte a múltiplos idiomas.  

---

## 📝 Prompt Original (PRD)

> Clique no botão de copiar no canto superior direito para usar este prompt no Lovable.

```text
Gostaria que me ajudasse a revisar esse meu PRD (Product Requirements Document), pois pretendo usá-lo no Lovable para exercitar minhas skills de Vibe Coding. Poderia me ajudar? Como resposta me mande o PRD revisado e sintetize de forma didatica os conceitos de Vibe Coding e PRD, pois ainda estou aprendendo sobre eles!

# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural, e que seja facilmente integrado ao App do banco que o usuário utilize. 
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.  
6. Ser avisado quando ultrapassar o orçamento mensal.  
7. Deve ser facilmente integrado com o App do banco que o cliente usa.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.


## ✅ Checklist de Design Universal

O MoneyStack deve seguir os princípios de **Design Universal**, garantindo que o app ofereça uma boa experiência para o máximo de usuários possíveis.  
Aqui estão pontos práticos para guiar a implementação:

- **Acessibilidade Visual**
  - Usar contraste adequado entre texto e fundo.
  - Permitir ajuste de tamanho de fonte.
  - Evitar depender apenas de cores para transmitir informações.

- **Acessibilidade Auditiva**
  - Oferecer alternativas visuais para notificações sonoras.
  - Possibilidade de interação por texto em vez de áudio.

- **Acessibilidade Motora**
  - Botões grandes e fáceis de clicar.
  - Suporte a navegação por teclado e comandos de voz.

- **Clareza e Simplicidade**
  - Linguagem natural e acessível.
  - Fluxos de interação curtos e intuitivos.
  - Evitar jargões técnicos.

- **Flexibilidade**
  - Permitir múltiplas formas de interação (chat, voz, notificações).
  - Personalização de relatórios e metas conforme perfil do usuário.

- **Inclusão**
  - Considerar diversidade cultural e linguística.
  - Suporte a diferentes idiomas.
  - Experiência consistente para iniciantes e usuários avançados.

---

## 📚 O que é Design Universal?

- **Definição:** É uma filosofia de design que busca criar produtos e serviços que possam ser usados pelo **maior número possível de pessoas**, sem necessidade de adaptações especiais.  
- **Objetivo:** Tornar o app inclusivo, acessível e agradável para todos, independentemente de idade, experiência ou possíveis limitações.  
- **Exemplo prático:** Um botão grande e com texto claro ajuda tanto quem tem dificuldades visuais quanto quem está usando o app em movimento.

👉 Em resumo: **Design Universal = criar soluções inclusivas, acessíveis e fáceis de usar para todos.**


