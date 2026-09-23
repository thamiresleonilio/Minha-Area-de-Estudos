# 🧶 Caderno Temático: O Artesanato como Meditação Ativa

Este repositório contém o projeto final do Desafio de Projeto da DIO, focado no uso do Google NotebookLM para criar um Caderno Temático.

## 🎯 Contexto e Objetivos

**Contexto:** 
Eu sempre tive muito interesse por assuntos sobre espiritualidade e Artesanatos de diferentes técnicas. Sempre fui muito auditada nesses assuntos, meio que um hiperfoco(rsrsr), isso era natural pra mim. Quando eu tinha 9 anos não deixei minha mãe em paz enquanto ela não me ensinasse pontos básicos em crochê, com 3 dias depois saiu a minha primeira blusa. Assim foi com o macramé, velas aromáticas, difusores e tudo que me interessava no mundo Hand made. Quando estou fazendo uma peça a mão, é como se só existisse aquilo. A mente silencia, volto ao momento presente, e isso traz uma paz. Algo de sobrenatural acontece é onde me conecto com meu Eu. Consigo ter mais clareza mental para tomar decisões mais assertivas. Por isso, escolhi este tema porque queria usar a Inteligência Artificial para entender melhor a ciência e a filosofia por trás do foco, da calma e da presença que as artes manuais nos proporcionam.

**Objetivos de Estudo:**
Através deste caderno temático, busco utilizar o NotebookLM para:
1. Compreender como atividades como o crochê, macramé afetam a mente humana.
2. Identificar a relação entre trabalhos manuais e práticas de mindfulness (atenção plena).
3. Criar um guia para ajudar iniciantes a usar o artesanato para aliviar a ansiedade.

## 🧠 Engenharia de Prompts e "Cicatrizes"

Durante o desenvolvimento deste caderno, testei diferentes formas de interagir com o NotebookLM para extrair as melhores informações. Abaixo estão os registros dos meus testes (troubleshooting):

### Teste 1: Buscando os benefícios do artesanato
* **Prompt Inicial (Tentativa 1):** "Quais são os benefícios do artesanato segundo os textos?"
* **A "Cicatriz" (O que deu errado):** A resposta foi muito superficial, não citou as fontes e pareceu um texto genérico de internet.
* **O Refinamento (Prompt Melhorado):** "Com base nos documentos fornecidos, aja como um terapeuta ocupacional e liste os 3 principais benefícios do artesanato para a redução da ansiedade. Formate a resposta em tópicos e referencie os textos."
* **Resultado:** Uma resposta mais concisa, com referencia e tópicos. Como fosse um profissional da área terapêutica. "A execução de trabalhos manuais atua diretamente na autorregulação emocional e fisiológica, baixando os níveis de hormônios do estresse (como o cortisol) e estimulando a liberação de neurotransmissores associados ao bem-estar, como a serotonina e a dopamina"

### Teste 2: Criando um Guia de Atenção Plena com Macramé
* **Prompt Inicial:** Gostaria de ver o guia de mindfulness aplicado ao artesanato.
* **A "Cicatriz":** Resposta genérica, confusa no passo a passo e não explicou o porque de esta fazendo determinada ação.
* **O Refinamento:** Elabore um protocolo simples de 5 minutos de atenção plena (mindfulness) ancorado no fazer macrame para praticar no dia a dia. Liste dicas práticas para cada ação e explique cada uma delas.
* **Resultado:** Bem estruturado, explicando cada ação e explicação cientifica com dicas práticas de cada passo a passo:
"Minuto 3: Repetição Rítmica do Nó Quadrado ou Espiral (Estado de Flow)
Ação: Executar uma sequência contínua e ritmada do nó quadrado ou do nó espiral básico.
Dica Prática: Acompanhe o movimento do fio guia cruzando o centro e sinta o toque dos dedos ao ajustar a firmeza exata de cada amarra. Mantenha um ritmo fluido e constante.
Explicação: A repetição de padrões e nós induz o estado de flow (fluxo), no qual a ação e a consciência se fundem e o tempo parece passar mais devagar. Essa imersão acalma a amígdala (região cerebral associada ao estresse) e reduz temporariamente a atividade do córtex pré-frontal responsável pela autocrítica e preocupações

### Teste 3: Criando um Glossário
* **Prompt Inicial:** O que é meditação ativa, mindfulness e flow segundo os textos?
* **A "Cicatriz":** Mencionou apenas 3 termos com explicações imensas, saindo do contexto que foi solicitado, parecendo um copia e cola dos textos bases.
* **O Refinamento:** Aja como um professor. Analise os documentos e crie um glossário com os 5 principais termos que ligam o artesanato ao bem-estar mental (por exemplo: Mindfulness, Estado de Flow, Meditação Ativa, etc). Formate a resposta com o Nome do termo em negrito, seguido de uma explicação simples de no máximo 2 linhas para cada.
* **Resultado:** Resposta muito bem colocada, coesa e limpa. Com termos em negritos, feitos em bullets points e com explicação simples e fácil de entender.

### 2. Glossário

**Mindfulness (Atenção Plena):** Prática deliberada de focar a consciência nas sensações, movimentos e texturas do trabalho manual no momento presente, afastando distrações e julgamentos.
**Estado de Flow (Fluxo):** Imersão profunda na atividade em que a ação e a consciência se fundem, a percepção do tempo se distorce e o monitoramento autocrítico interno é desativado.
**Meditação Ativa:** Processo de desaceleração da mente induzido pela repetição cadenciada e ritmada dos movimentos manuais, servindo como uma âncora sensorial no "aqui e agora".
**Reserva Cognitiva:** Proteção cerebral fortalecida pelo desafio constante de aprender pontos novos, ler gráficos e resolver problemas manuais, estimulando a memória e a neuroplasticidade.
**Arteterapia:** Uso de linguagens artísticas e técnicas manuais expressivas como canal terapêutico para externalizar conflitos do inconsciente, aliviar o estresse e promover a reconexão emocional.

### 1. Resumo Estruturado: Mãos que Curam a Mente

Em um mundo acelerado e hiperconectado, onde a urgência constante e a exposição às telas geram fadiga digital e estresse frequente, o fazer manual deixou de ser visto como um simples passatempo ocupacional para se consolidar como um verdadeiro santuário de preservação emocional. Enquanto o universo virtual exige performance ininterrupta e respostas imediatas, o ato de trançar, bordar, tecer ou modelar pede presença, zelo e tempo. Essa pausa deliberada funciona como um contraponto essencial ao ruído cotidiano, transformando gestos simples em uma oportunidade concreta de desaceleração, escuta interior e reconexão pessoal.
A ciência e a neurociência confirmam o que os praticantes já sentiam na pele: a criação com as mãos altera profundamente a fisiologia e a química do cérebro. A repetição cadenciada e rítmica dos movimentos manuais acalma a amígdala cerebral, desacelera a frequência cardíaca e reduz os níveis sanguíneos do hormônio do estresse (o cortisol), ao mesmo tempo em que estimula a liberação de neurotransmissores como a dopamina e a serotonina. Essa imersão tátil induz a mente a estados de atenção plena (mindfulness) e fluxo (flow), nos quais as preocupações diárias e a autocrítica se silenciam, aliviando de forma direta os sintomas de ansiedade, depressão e esgotamento mental.
Para além do relaxamento imediato, o trabalho manual atua como um poderoso catalisador de reconstrução interna, restaurando a autoestima, a autonomia e o sentimento de eficácia pessoal. Ver uma peça ganhar forma a partir do zero ativa o sistema de recompensa cerebral a cada etapa concluída, nutrindo um ciclo sustentável de resiliência e autocompaixão. Além disso, ao introduzir desafios constantes e o aprendizado de técnicas complexas, a prática estimula a neuroplasticidade e fortalece a reserva cognitiva do cérebro, provando que, ao entrelaçarmos fios, linhas ou argila, estamos, na verdade, tecendo a nossa própria cura e saúde mental.


### 3. Prompts Reutilizáveis

Aqui estão prompts estratégicos que criei e que você pode usar no NotebookLM para continuar estudando:
 
 *"Aja como um professor de artes manuais. Me dê 3 ideias de projetos de artesanato para iniciantes, focados estritamente em acalmar a mente e fáceis de fazer."*
 
* *"Explique a relação entre trabalhos manuais repetitivos e a redução do cortisol, citando estudos científicos ou fontes confiáveis."*

* Elabore um protocolo simples de 5 minutos de atenção plena (mindfulness) ancorado no fazer macrame para praticar no dia a dia. Liste dicas práticas para cada ação e explique cada uma delas.
