# Caderno-Tematico-NotebookLM
Projeto desenvolvido para o desafio da DIO utilizando NotebookLM, para criação de um caderno temático.
# Introdução

O presente projeto foi criado a partir da escolha de um tema que foi trazido através de um insight sobre a frase **“Finanças introdutórias”**, nada mais ideal do que começar pelo início **“Planejamento Financeiro Pessoal”**, o objetivo é que possa ser um guia de estudos para aprender sobre finanças pessoais, por onde começar, o que fazer e o que não fazer, o que levar para a pratica do dia a dia, e com esse aprendizado saber investir, seja em algo material ou na qualidade de vida.

# Fontes

- https://educapes.capes.gov.br/bitstream/capes/430564/2/Apostila%20B%C3%A1sico%20em%20Finan%C3%A7as%20Pessoais.pdf
- https://conteudos.xpi.com.br/aprenda-a-investir/relatorios/planejamento-financeiro/
- https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm/livro-top-planejamento-financeiro-pessoal/@@display-file/file
- https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf

# Prompts

## Prompt 1

Para esta pergunta foram utilizadas instruções claras, separadas por tópicos para que fique mais organizado e detalhado, foram feitas indicações e um formato de saída, para especificar a forma de respostas.

### Prompt

> **Tarefa:** Me introduza sobre os assuntos de finanças pessoais
>
> **Contexto:** Ensine de forma dinâmica e didática, de uma forma que seja de fácil entendimento. Faça definições em poucas palavras e use exemplos práticos do dia a dia.

### Resposta

> Dominar as finanças pessoais é o primeiro passo para transformar seus sonhos em realidade e ter uma vida mais tranquila. Vamos explorar os conceitos principais de forma rápida e prática:
>
> **1. O Orçamento: O Mapa do Tesouro**
>
> - **O que é:** Registrar e controlar tudo o que você ganha e o que você gasta.
> - **A Regra de Ouro:** O objetivo é ser superavitário, ou seja, gastar menos do que se recebe.
> - **Exemplo Prático:** Anotar cada cafezinho ou passagem de ônibus em um caderninho ou aplicativo para saber exatamente para onde seu dinheiro está indo no fim do mês.
>
> **2. Necessidades vs. Desejos**
>
> - **Necessidades:** Coisas indispensáveis para viver.
> - **Desejos:** Coisas que queremos ter, mas que não são essenciais.
> - **Exemplo Prático:** Comprar arroz e feijão é uma necessidade; jantar em um restaurante de luxo com pratos caros é um desejo.
>
> **3. Custo de Oportunidade: A Troca**
>
> - **O que é:** O benefício que você deixa de ganhar ao escolher uma coisa em vez de outra.
> - **Exemplo Prático:** Se você decide gastar R$ 1.000 em uma viagem curta agora, o seu custo de oportunidade é o que esse dinheiro renderia se estivesse investido para uma viagem maior no ano que vem.
>
> **4. Juros Compostos: O Dinheiro Trabalhando**
>
> - **O que é:** Conhecido como "juros sobre juros". O rendimento é calculado sobre o valor inicial mais os juros que já renderam antes.
> - **Exemplo Prático:** Se você investe R$ 100 com 8% de juros ao mês, no segundo mês você ganhará juros sobre R$ 108, e não apenas sobre os R$ 100 iniciais.
>
> **5. Crédito: Um Aliado Perigoso**
>
> - **O que é:** Usar o dinheiro de terceiros (bancos) para comprar algo agora e pagar depois.
> - **O Perigo:** Ele tem um preço (juros) e tira dinheiro do seu orçamento futuro.
> - **Exemplo Prático:** Parcelar uma compra no cartão de crédito quando você não tem o dinheiro hoje; você antecipa o consumo, mas terá prestações para pagar depois.
>
> **6. Reserva de Emergência: O Seu Seguro**
>
> - **O que é:** Dinheiro guardado exclusivamente para imprevistos.
> - **Quanto guardar:** Recomenda-se ter guardado o equivalente a 3 a 6 meses das suas despesas mensais.
> - **Exemplo Prático:** Ter aquele dinheiro guardado para quando a geladeira estraga ou surge um problema de saúde inesperado, evitando que você precise pedir um empréstimo caro.
>
> **7. Investimento: Multiplicando o Patrimônio**
>
> - **O que é:** Aplicar o que você poupou para que esse dinheiro gere mais dinheiro.
> - **O Tripé:** Todo investimento deve ser avaliado por sua rentabilidade (ganho), liquidez (rapidez para sacar) e risco (segurança).
> - **Exemplo Prático:** Em vez de deixar o dinheiro "parado" em casa, colocá-lo no Tesouro Direto ou em um CDB para que ele renda juros ao longo do tempo.
>
> **Dica de Ouro:** "Pague-se primeiro". Assim que receber seu salário, separe logo a parte da sua reserva ou investimento antes de começar a pagar as contas.

## Refinamento de Prompt 1

A IA retornou uma boa resposta, porém pensando para iniciantes uma linguagem ainda menos técnica facilita o entendimento, por isso o prompt foi modificado para especificar mais um pouco o público alvo e os termos que não deve usar, usando restrições e limitações a ia foi capaz de melhorar suas respostas.

### Prompt

> **Tarefa:** Me introduza sobre os assuntos de finanças pessoais
>
> **Contexto:** Ensine de forma dinâmica e didática, de uma forma que seja de fácil entendimento para iniciantes, usando menos termos técnicos. Faça definições em poucas palavras e use exemplos práticos do dia a dia.

**Obs:** Para esse prompt foi dada instruções onde houveram, o formato da resposta, foram usados few-shot-learning e indicações para dar uma especificação, com um contexto definido, além de nos exemplos foram dados conteúdos de suporte para uma resposta acurada.

### Resposta

> Entender de finanças pessoais é aprender a gerir o seu dinheiro para realizar seus sonhos e ter uma vida mais tranquila. Aqui estão os principais conceitos explicados de forma simples:
>
> **1. Planejamento Financeiro: O Seu Mapa**
>
> Planejar é traçar o caminho que você quer percorrer para alcançar um objetivo definido.
>
> - **Exemplo Prático:** Se você sonha em comprar uma moto de R$ 24 mil em dois anos, o planejamento será poupar R$ 1 mil por mês para comprá-la à vista e ainda conseguir um desconto.
>
> **2. Orçamento: O Registro dos Passos**
>
> É o plano onde você registra tudo o que ganha (receitas) e tudo o que gasta (despesas). A regra de ouro é manter o orçamento superavitário, ou seja, gastar sempre menos do que você recebe.
>
> - **Exemplo Prático:** Anotar cada cafezinho ou lanche em uma planilha ou caderninho para descobrir para onde seu dinheiro está indo.
>
> **3. Necessidade vs. Desejo: A Escolha Consciente**
>
> Saber diferenciar esses dois é essencial para manter a saúde do seu bolso.
>
> - **Necessidades:** São coisas indispensáveis para viver, como moradia, saúde e alimentação básica.
> - **Desejos:** São coisas que queremos ter para nosso prazer, mas que não são essenciais, como jantar em um restaurante de luxo ou comprar roupas de marca.
>
> **4. Custo de Oportunidade: A Troca**
>
> É o preço da renúncia: o que você deixa de ganhar ao escolher uma coisa em vez de outra.
>
> - **Exemplo Prático:** Se você usar um dinheiro extra para uma viagem curta agora, o seu "custo" é o que esse dinheiro renderia se estivesse investido para uma viagem maior no futuro.
>
> **5. Juros Compostos: O Tempo a Seu Favor**
>
> Conhecidos como "juros sobre juros", eles fazem o dinheiro crescer de forma muito rápida ao longo dos anos.
>
> - **Exemplo Prático:** Uma pessoa que começa a poupar R$ 150 por mês aos 20 anos acumulará muito mais dinheiro com menos esforço do que alguém que só começa aos 30 anos.
>
> **6. Crédito: O Dinheiro "Alugado"**
>
> Crédito é usar o dinheiro de bancos ou financeiras para comprar algo agora e pagar no futuro. O problema é que isso tem um custo (juros) que pode virar uma bola de neve e tirar dinheiro do seu orçamento futuro.
>
> **7. Reserva de Emergência: O Seu Porto Seguro**
>
> É um dinheiro guardado exclusivamente para imprevistos, como um problema de saúde ou a perda do emprego. Recomenda-se ter guardado o equivalente a 3 a 6 meses do valor das suas despesas mensais.
>
> **8. Investimento: Fazendo o Dinheiro Trabalhar**
>
> Investir é aplicar o dinheiro que você poupou para que ele gere mais dinheiro (rendimentos). Todo investimento deve ser avaliado por três pontos:
>
> 1. **Risco:** O perigo de perder dinheiro.
> 2. **Liquidez:** A facilidade de transformar o investimento em dinheiro vivo de novo.
> 3. **Rentabilidade:** O quanto o dinheiro vai render de fato.



### Prompt2

Para este prompt foi solicitado que a IA criasse uma história em formato de comédia para contextualizar conceitos de educação financeira em uma situação do cotidiano.

### Prompt

> **Escreva uma história de comedia, que seja curta com início meio e fim, sobre uma mulher de 25 anos chamada Beck que está endividada por causa de sua paixão por moda que a fez que fizesse compras impulsivas de roupas, acessórios e sapatos, e que por isso precisa urgentemente aprender finanças pessoais para sair da situação atual em que se encontra.**

### Resposta

> Beck, aos 25 anos, vivia em um verdadeiro "museu da moda" financiado integralmente pelo banco. Seu guarda-roupa transbordava com peças que ela comprou apenas para manter o status, muitas vezes usando dinheiro que não tinha para impressionar pessoas de quem nem gostava. O ápice da comédia trágica ocorreu quando ela tentou pagar o aluguel com um par de sapatos de grife, percebendo que estava em uma situação de endividamento excessivo e que precisava urgentemente "parar de cavar" para sair do buraco financeiro.
>
> Determinada a mudar, Beck abriu um caderno de educação financeira e descobriu que era uma vítima perfeita do "marketing de sedução", que despertava seu lado emocional e irracional na hora das compras. Ela entendeu que sofria do "viés do presente", priorizando o prazer imediato de um acessório novo em vez de sua segurança futura. Beck então sentou para fazer um diagnóstico de sua situação atual, listando todas as suas dívidas, taxas de juros e prazos de pagamento. Para organizar a bagunça, ela usou o Diagrama de Ishikawa, agrupando seus gastos e descobrindo que a categoria "mimos para mim mesma" era a grande vilã do seu orçamento.
>
> Na fase final de sua transformação, Beck aplicou o Princípio de Pareto, percebendo que apenas 20% de seus hábitos de consumo impulsivo geravam 80% de suas dívidas. Ela aprendeu a distinguir rigorosamente necessidades de desejos, aceitando que, embora uma bolsa nova fosse um anseio legítimo, apenas a alimentação e o transporte eram indispensáveis. Com disciplina, ela começou a se "pagar primeiro", separando uma quantia para sua reserva de emergência antes de sequer olhar as vitrines. Hoje, Beck prefere o brilho de um orçamento superavitário ao de qualquer lantejoula, caminhando firme rumo à sua liberdade financeira.

**Obs:** Apesar da história ter ficado muito boa, foram usados alguns termos técnicos que ficaram sem explicação, dificultando o entendimento, então o refinamento focou em especificar reajustar esses termos para um melhor entendimento.

## Refinamento de Prompt 2

### Prompt

> **Escreva uma história de comedia, que seja curta com início meio e fim, usando termos comuns e menos técnicos. sobre uma mulher de 25 anos chamada Beck que está endividada por causa de sua paixão por moda que a fez que fizesse compras impulsivas de roupas, acessórios e sapatos, e que por isso precisa urgentemente aprender finanças pessoais para sair da situação atual em que se encontra.**

### Resposta

**Obs:** Apesar da história ter ficado muito boa, foram usados alguns termos técnicos que ficaram sem explicação, dificultando o entendimento, então o refinamento focou em especificar reajustar esses termos para um melhor entendimento.

> Beck, aos 25 anos, vivia em um "closet de luxo" que, na verdade, pertencia ao banco. O ápice de sua comédia trágica aconteceu quando ela tentou comprar um café com "charme" e o cartão foi recusado, forçando-a a encarar uma pilha de faturas que crescia mais rápido que as tendências de Milão. Beck percebeu que sofria de consumismo, comprando por impulso sem necessidade real, levada pelo "marketing de sedução" das vitrines que falavam diretamente com sua emoção e não com sua razão.
>
> Determinada a sair do "buraco", Beck entendeu que a primeira regra era "parar de cavar". Ela sentou-se para fazer um diagnóstico de sua situação, anotando cada centavo que ganhava e, principalmente, cada par de sapatos que ainda devia. Beck aprendeu a diferença cruel entre necessidade e desejo: enquanto comida era essencial, aquela bolsa de grife era apenas um sonho caro que ela tratava como se fosse oxigênio. Ela descobriu que sua paixão por moda a fazia focar no prazer imediato, esquecendo-se de que o consumo antecipado tem um preço alto chamado juros, que faz a dívida virar uma bola de neve.
>
> Para retomar o controle, Beck decidiu renegociar suas dívidas com o banco, trocando juros caros por parcelas que realmente coubessem no seu bolso. Ela adotou a estratégia de "pagar-se primeiro", separando uma quantia para sua reserva de emergência assim que o salário caía, antes mesmo de pensar em olhar as promoções. Beck trocou as idas impulsivas ao shopping por um orçamento superavitário, onde suas despesas eram sempre menores que seus ganhos. Hoje, ela desfila com orgulho não apenas roupas novas, mas a segurança de quem está no caminho da liberdade financeira.

## Prompt 3

Para este prompt foi feito uma divisão de tarefas, separado por tópicos onde instruem e indicam como deve ser feito e escrito e para quem é direcionado.

### Prompt

> **Instrução:** Faça uma lista dos principais termos usados na educação financeira pessoal
>
> **Contexto:** Deve ser organizado por nível de importância, ter os termos e uma curta definição de cada de forma clara e de fácil entendimento para o público iniciante.

### Resposta

> Para ajudar você a dominar o mundo do dinheiro, aqui está uma lista dos termos fundamentais da educação financeira, organizados dos conceitos mais básicos (base) até os mais avançados (multiplicação), com definições simples e diretas:
>
> **Nível 1: A Base (Organização)**
>
> - **Educação Financeira:** É o processo de desenvolver conhecimentos e comportamentos para gerir o dinheiro de forma consciente e responsável, visando o bem-estar atual e futuro.
> - **Planejamento Financeiro:** É o "mapa" que você traça para organizar sua vida, definindo metas e estratégias para alcançar seus sonhos e objetivos.
> - **Orçamento:** É o registro de tudo o que você ganha (receitas) e tudo o que gasta (despesas) em um período para manter o equilíbrio das contas.
> - **Necessidades vs. Desejos:** Necessidades são coisas indispensáveis para viver (como comida e moradia); desejos são coisas que queremos para nosso prazer, mas não são essenciais.
>
> **Nível 2: A Execução (Equilíbrio)**
>
> - **Superávit Financeiro:** É a situação ideal em que suas receitas são maiores que suas despesas, permitindo que sobre dinheiro para poupar.
> - **Déficit Financeiro:** Ocorre quando as despesas superam os ganhos, levando ao endividamento.
> - **Custo de Oportunidade:** É o benefício que você deixa de ganhar ao escolher uma opção em vez de outra (ex: ao comprar algo agora, você perde o que aquele dinheiro renderia no futuro).
> - **Troca Intertemporal:** É a escolha entre consumir agora e pagar depois (pagando juros) ou poupar agora para consumir melhor no futuro (recebendo juros).
>
> **Nível 3: A Segurança (Proteção)**
>
> - **Reserva de Emergência (ou PMS):** Dinheiro guardado exclusivamente para imprevistos (saúde, desemprego), recomendado entre 3 a 6 meses de suas despesas mensais.
> - **"Pague-se Primeiro":** Estratégia de separar a parte da sua poupança assim que recebe o salário, antes de começar a pagar as contas do mês.
> - **Juros Compostos:** São os "juros sobre juros", onde o rendimento cresce sobre o valor total acumulado anteriormente, fazendo o dinheiro crescer de forma acelerada no longo prazo.
>
> **Nível 4: O Crédito (Cuidado)**
>
> - **Crédito:** Dinheiro de terceiros (bancos) que você usa hoje para pagar depois, geralmente com um custo adicional.
> - **Juros:** É o "aluguel" cobrado pelo uso do dinheiro; pode trabalhar contra você nas dívidas ou a seu favor nos investimentos.
> - **CET (Custo Efetivo Total):** É a taxa real de um empréstimo, que inclui não só os juros, mas também todas as taxas, impostos e encargos da operação.
>
> **Nível 5: O Futuro (Investimentos)**
>
> - **Investimento:** É aplicar seu dinheiro poupado em algo que gere uma remuneração (lucro ou juros).
> - **Liquidez:** É a velocidade e facilidade com que você consegue transformar um investimento de volta em dinheiro vivo no bolso.
> - **Perfil de Investidor:** É a classificação do seu apetite ao risco (Conservador, Moderado ou Arrojado), fundamental para escolher onde aplicar seu dinheiro.
> - **Renda Fixa vs. Renda Variável:** Na Renda Fixa, você conhece ou estima as regras de rendimento no início; na Renda Variável (como ações), o retorno não é garantido e pode oscilar muito.

**Obs:** Essa resposta foi bastante satisfatória, foi executada de forma muito alinhada com o que foi pedido, além de trazer uma linguagem de fácil entendimento.
## Prompt 4

Para esse prompt foi usado uma forma bastante eficaz de trazer respostas satisfatórias usando introduções claras, contexto, dando indicações e limitações, fechando com um formato de saída.

### Prompt

> **Atue como um especialista em educação financeira que atua como um professor para iniciantes, e fale sobre os 3 principais erros financeiros cometidos pelas pessoas, e depois explique como reparar eles. Explique como se fosse uma aula.**

### Resposta

> **Bom dia, turma!** Sejam bem-vindos à nossa aula sobre os fundamentos da saúde financeira. Hoje, vamos identificar os comportamentos que mais sabotam o bolso dos brasileiros e, o mais importante, aprender como virar esse jogo. Como sempre digo: mais importante do que saber ganhar dinheiro é saber gastá-lo.
>
> Peguem seus cadernos, pois vamos analisar os **3 principais erros financeiros e suas respectivas soluções.**
>
> ---
>
> ### Erro 1: A Mania de Não Planejar (Procrastinação)
>
> Muitas pessoas têm o hábito de adiar a organização de suas finanças, focando apenas no presente e deixando para "amanhã" o que deveria ser controlado hoje. Sem um mapa, você não sabe para onde seu dinheiro está indo e acaba sendo pego de surpresa por despesas sazonais (como IPTU, IPVA ou material escolar) que, na verdade, poderiam ter sido previstas.
>
> **Como reparar:**
>
> O primeiro passo é fazer um diagnóstico da sua situação atual. Você precisa anotar todas as suas receitas e despesas, inclusive os centavos. Utilize uma planilha, um aplicativo ou até um caderninho para registrar tudo o que ganha e gasta. Só assim você entenderá sua realidade e poderá traçar metas claras e realistas para o futuro.
>
> ---
>
> ### Erro 2: Gastar Mais do que se Ganha (Orçamento Deficitário)
>
> Este é um erro clássico: viver um padrão de vida acima da sua renda real. Muitas vezes, as pessoas gastam tudo o que recebem e não reservam nada para o futuro, tratando desejos passageiros como se fossem necessidades indispensáveis.
>
> **Como reparar:**
>
> Aprenda a regra de ouro: **"Pague-se primeiro"**. Assim que receber seu salário, separe uma parte (idealmente entre 10% a 20%) para seus sonhos e reserva de segurança antes mesmo de pagar as contas do mês. Além disso, você deve classificar seus gastos: elimine os desperdícios (como multas ou serviços que não usa), reduza os supérfluos e otimize os necessários.
>
> ---
>
> ### Erro 3: O Uso Indiscriminado do Crédito para Consumo
>
> O uso inadequado do cartão de crédito e do cheque especial é uma das maiores armadilhas modernas. Ao parcelar compras de consumo ou pagar apenas o mínimo da fatura, você entra em uma "bola de neve" de juros altíssimos, comprometendo sua renda futura com algo que já foi consumido.
>
> **Como reparar:**
>
> Se você já está no buraco, a primeira regra é **"parar de cavar"**. Pare de fazer novas dívidas imediatamente. O próximo passo é mapear suas dívidas (valores, prazos e taxas de juros) e buscar a renegociação com os credores, tentando trocar juros caros por opções mais baratas ou prazos que caibam no orçamento. Paralelamente, comece a construir sua reserva de emergência (ou Patrimônio Mínimo de Sobrevivência), que deve ser equivalente a 3 a 6 meses das suas despesas mensais, para evitar recorrer ao crédito em imprevistos futuros.
>
> ---
>
> ### Resumo da aula
>
> Para ter uma vida financeira saudável, você precisa de **diagnóstico** (saber onde está), **disciplina** (gastar menos do que ganha) e **proteção** (ter uma reserva para emergências e evitar dívidas de consumo).
>
> Alguma dúvida até aqui? Lembre-se que a educação financeira é um processo contínuo e o primeiro passo é a mudança de comportamento. Aula encerrada!

---

# Observação Geral

Para construir um bom prompt é preciso ter instruções claras, sempre que possível especificando, organizando, fazendo restrições e limitações ajustando a entrada e saída, para que a IA entregue exatamente aquilo que foi pedido. E nestes prompts foram usadas algumas dessas técnicas, notando-se que quando se especifica organizadamente e divide os comandos se obtém respostas mais satisfatórias.
# Miniguia de Estudo

## Resumo

Abaixo, resumo dos temas centrais apresentados:

### 1. Planejamento Financeiro e Educação

O planejamento é descrito como um processo dinâmico que visa organizar a vida financeira por meio de estratégias para atingir objetivos de vida e transformar sonhos em projetos concretos. A educação financeira é o meio de promover comportamentos conscientes para gerir recursos de forma responsável, buscando o bem-estar atual e futuro.

### 2. Orçamento e Fluxo de Caixa

Um ponto central em todos os materiais é a necessidade de registrar e controlar receitas e despesas. O objetivo primordial de um orçamento bem estruturado é ser superavitário, ou seja, garantir que as despesas sejam inferiores aos ganhos, permitindo a formação de poupança.

As fontes recomendam:

- Diferenciar necessidades (indispensáveis) de desejos (supérfluos).
- Diferenciar gastos fixos de variáveis para melhor ajuste das contas.
- A estratégia do **"pague-se primeiro"**, reservando uma parte da renda para investimentos logo após o recebimento do salário.

### 3. Gestão de Crédito e Dívidas

O uso do crédito é apresentado como uma ferramenta para antecipar o consumo ou construir patrimônio, mas que exige cautela devido ao custo dos juros. As fontes alertam sobre o perigo do endividamento excessivo, recomendando o mapeamento de dívidas e a renegociação para trocar juros caros por opções mais baratas. O conceito de **Custo Efetivo Total (CET)** é destacado como essencial para comparar o custo real de empréstimos.

### 4. Reserva de Emergência

A formação de um fundo de reserva (ou Patrimônio Mínimo de Sobrevivência) é considerada uma prioridade de segurança. Recomenda-se que esse valor seja equivalente a **3 a 6 meses** das despesas mensais para enfrentar imprevistos sem recorrer a dívidas.

### 5. Investimentos e o Tripé Financeiro

Para multiplicar o patrimônio, as fontes ensinam que todo investimento deve ser avaliado com base no tripé:

- Risco;
- Liquidez;
- Rentabilidade.

Além disso, destacam a importância de identificar o perfil do investidor (**conservador, moderado ou arrojado**) para escolher aplicações compatíveis com o apetite ao risco e os prazos desejados.

### 6. Planejamento da Aposentadoria e Futuro

Preparar-se para a inatividade é um tema recorrente, enfatizando que quanto mais cedo começar, menor será o aporte necessário devido ao poder dos juros compostos ao longo do tempo. São discutidas opções como a previdência social (INSS), previdência complementar (PGBL/VGBL) e a acumulação própria de ativos.

### 7. Gestão de Riscos e Seguros

Por fim, as fontes abordam a proteção contra eventos incertos que podem comprometer o patrimônio. O seguro é apresentado como um instrumento de transferência de risco para uma seguradora, garantindo tranquilidade em casos de doenças, acidentes ou perdas materiais.
# Glossário

Com base no resumo dos temas, esse glossário trás os termos fundamentais para quem está iniciando no planejamento financeiro pessoal:

## 1. Organização e Educação

- **Educação Financeira:** É o meio de promover comportamentos que melhoram o bem-estar e a cidadania financeira, permitindo gerir recursos de forma consciente.
- **Planejamento Financeiro:** Processo dinâmico de organizar a vida financeira por meio de estratégias para atingir objetivos e sonhos de vida.
- **Orçamento Pessoal:** Plano ou ferramenta de registro e controle de todas as entradas (receitas) e saídas (gastos) de dinheiro.
- **Superávit Financeiro:** Situação em que as receitas são superiores às despesas, permitindo a formação de poupança.
- **Déficit Financeiro:** Ocorre quando as despesas superam os ganhos, levando ao desequilíbrio das contas e ao endividamento.
- **Necessidades:** Coisas indispensáveis para a vida, como alimentação e moradia.
- **Desejos:** Anseios e vontades que queremos possuir para prazer, mas que não são essenciais para a sobrevivência.

## 2. Execução e Comportamento

- **Custo de Oportunidade:** Representa o benefício que se deixa de ganhar ao fazer uma escolha em vez de outra (o "preço da renúncia").
- **Troca Intertemporal:** A escolha entre consumir hoje e pagar depois (assumindo juros) ou poupar agora para consumir com rendimentos no futuro.
- **"Pague-se Primeiro":** Estratégia de reservar a parte destinada aos investimentos imediatamente após receber o salário, antes de pagar as contas do mês.

## 3. Crédito e Dívidas

- **Crédito:** Recurso obtido de terceiros (bancos) que permite antecipar o consumo, gerando uma obrigação de pagamento futuro.
- **Juros:** É o "aluguel" cobrado pelo uso do dinheiro no tempo; pode ser o custo de uma dívida ou a remuneração de um investimento.
- **Juros Compostos:** "Juros sobre juros"; sistema onde os rendimentos são incorporados ao capital a cada período, gerando crescimento exponencial.
- **Custo Efetivo Total (CET):** Taxa real que inclui juros, tarifas, impostos e outros encargos, permitindo comparar o custo total de diferentes empréstimos.

## 4. Segurança e Investimentos

- **Reserva de Emergência (ou PMS):** Reserva financeira equivalente a 3 a 6 meses de despesas, destinada exclusivamente para imprevistos (saúde, desemprego).
- **Investimento:** Aplicação de recursos poupados com a expectativa de obter uma remuneração ou lucro futuro.
- **Liquidez:** A facilidade e rapidez com que um investimento pode ser transformado em dinheiro vivo sem perda de valor.
- **Risco:** Probabilidade de ocorrerem perdas financeiras no valor investido.
- **Rentabilidade:** O retorno ou remuneração efetiva de uma aplicação financeira.
- **Perfil de Investidor:** Classificação (conservador, moderado ou arrojado) baseada no apetite ao risco e nos objetivos do indivíduo.
- **Renda Fixa:** Investimento onde as regras de rendimento são definidas no início da aplicação.
- **Renda Variável:** Investimentos onde a remuneração não é garantida e pode oscilar (ex: ações).

## 5. Futuro e Proteção

- **Previdência Complementar:** Sistema opcional de acumulação de recursos para o futuro, dividido em PGBL (com benefício fiscal na declaração completa) e VGBL (sem benefício fiscal imediato, tributando apenas rendimentos).
- **Seguro:** Contrato pelo qual uma empresa se obriga a indenizar o segurado por prejuízos decorrentes de riscos previstos.
- **Prêmio:** Valor que o segurado paga à seguradora para ter direito à proteção do seguro.
- **Sinistro:** Ocorrência efetiva do risco coberto pelo seguro durante sua vigência.

# Prompts reutilizáveis

## Prompt 1

> **Tarefa:** Faça um pequeno resumo sobre a educação financeira pessoal.
>
> **Contexto:** Escreva com os principais termos em negrito e em parênteses as definições) de forma que iniciantes possam entender, sem usar termos técnicos difíceis.

---

## Prompt 2

> **Atue como um especialista em educação financeira que atua como um professor para iniciantes, e fale sobre os 3 principais erros financeiros cometidos pelas pessoas, e depois explique como reparar eles. Explique como se fosse uma aula.**

---

## Prompt 3

> **Tarefa:** Faça uma lista de 3 comportamentos que mais prejudicam a vida financeira de uma pessoa.
>
> **Contexto:** Explique de forma clara e de fácil entendimento, usando exemplos básicos.

---

## Prompt 4

> **Escreva uma história, que seja curta com início meio e fim, usando termos comuns e menos técnicos, sobre uma pessoa que está endividada por causa de compras impulsivas que por isso precisa urgentemente aprender finanças pessoais para sair da situação atual em que se encontra.**
