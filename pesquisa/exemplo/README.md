# Exemplo de Roteiro Preenchido <br> Projeto de Extensão em Eletrônica

**Projeto pesquisado:** Robótica Pedagógica com Arduino — IFC Campus Luzerna (SC)

**Finalidade:** modelo de referência, mostrando o nível de detalhe esperado no preenchimento do roteiro

---

## 1. Identificação do projeto

| Campo | Informação |
|---|---|
| **Nome do projeto** | Extensão Tecnológica e hardware livre: robótica pedagógica com Arduino nas escolas públicas do Meio-Oeste Catarinense |
| **Instituição de ensino** | Instituto Federal Catarinense (IFC) — Campus Luzerna, Santa Catarina |
| **Curso(s) vinculado(s)** | Engenharia de Controle e Automação; Técnico em Automação Industrial |
| **Área do conhecimento** | Eletrônica, automação e robótica educacional (área temática "Tecnologia e Produção") |
| **Período de duração** | Início em 01/11/2016; dados analisados até 28/07/2017. É continuação de uma ação iniciada em 2014 com kits Lego Mindstorms. **Situação atual não verificada** — a fonte consultada vai até 2017. |
| **Coordenação, equipe e financiamento** *(opcional)* | Coordenador: Prof. Illyushin Zaak Saraiva. Equipe de 5 professores, 3 bolsistas e 3 voluntários. Financiado pelas Pró-Reitorias de Pesquisa e de Extensão do IFC (edital 162/2016-Reitoria/IFC); a fase anterior contou com recursos do CNPq. |

---

## 2. Contexto e justificativa

**Qual problema ou necessidade social/comunitária o projeto busca resolver?**

Escolas públicas da região do Meio-Oeste catarinense têm pouco ou nenhum acesso a conteúdos de eletrônica, programação e robótica, e os professores dessas escolas raramente receberam formação nessas tecnologias. O conhecimento técnico produzido dentro do campus não chegava à comunidade do entorno.

O projeto se apoia na noção de *Extensão Acadêmica* (Jezine, 2004): uma troca de mão dupla entre o saber científico da equipe e o saber trazido pela comunidade escolar, em oposição a modelos apenas assistencialistas.

**Qual público-alvo é atendido?**

- Estudantes de escolas estaduais e municipais dos municípios no entorno de Luzerna
- Professores da rede pública, em oficinas de formação específicas
- Comunidades atendidas pelo Projeto Rondon

**Parceiros institucionais:** 7ª Gerência Regional de Educação da SED-SC (Joaçaba), Prefeitura de Joaçaba, escolas estaduais e municipais e o Projeto Rondon.

---

## 3. Metodologia e execução

**Quais atividades práticas são desenvolvidas?**

Oficinas de robótica pedagógica com duração de 2 a 4 horas, realizadas nas próprias escolas ou no campus, organizadas em duas fases:

1. **Fase teórica** — apresentação introdutória sobre robótica e sua evolução histórica, com projeção de slides.
2. **Fase prática** — operação de robôs seguidores de linha montados com kits Arduino, que percorrem uma pequena pista de corrida montada no local.

Antes de cada oficina, a equipe faz contato com a direção da escola e planeja a atividade de acordo com o perfil da turma. As oficinas também servem para levantar informações sobre o interesse de alunos e professores locais em robótica pedagógica.

**Quais conhecimentos técnicos/científicos da eletrônica são aplicados?**

O robô seguidor de linha percorre a cadeia clássica sensor → controlador → atuador:

| Etapa | Conteúdo técnico envolvido |
|---|---|
| Sensor óptico | Detecção da linha por refletância; condicionamento do sinal de entrada |
| Microcontrolador (Arduino) | Leitura das entradas, lógica de controle e programação embarcada |
| Driver de potência | Acionamento e controle dos motores a partir de sinais de baixa corrente |
| Motores DC | Conversão do sinal elétrico em movimento; tração diferencial |

Somam-se a isso a montagem física do circuito, a alimentação do conjunto e a integração hardware-software.

**Quais ferramentas, tecnologias ou metodologias são utilizadas?**

Plataforma Arduino (hardware livre / open source), kits montados pelos próprios bolsistas no campus, pista de teste portátil e material didático de apoio. A escolha pelo hardware livre é deliberada: reduz custo, permite a montagem interna dos robôs e torna a tecnologia replicável pelas escolas.

**Como se dá a interação entre os estudantes/equipe e a comunidade atendida?**

Os bolsistas de engenharia atuam diretamente como oficineiros — apresentam a parte teórica, operam os robôs com os estudantes e respondem às dúvidas. A relação é presencial e mediada pela escola, com articulação prévia junto à direção e à Gerência Regional de Educação.

---

## 4. Resultados e impactos

**Quais resultados concretos já foram alcançados?**

Resultados consolidados até 28/07/2017 (9 meses de projeto):

| Indicador | Meta original | Resultado alcançado |
|---|---|---|
| Municípios atendidos | 3 | 6, em 2 estados (SC e PI) |
| Oficinas realizadas | 6 | 12 |
| Participantes | 500 (até nov/2017) | 595 (já em jul/2017) |
| Artigos em congressos | 2 | 2 |

**Ações realizadas (amostra):**

- Oficinas em escolas de Joaçaba, Capinzal, Erval Velho e no próprio campus de Luzerna (SC)
- Oficina no Colégio Técnico de Floriano (UFPI), no Piauí, com 100 participantes
- Oficina de formação para professores da rede municipal de Joaçaba (25 participantes)
- 6 oficinas em Balneário Rincão (SC) dentro do Projeto Rondon, com mais de 300 participantes

**Houve impacto social, econômico ou ambiental mensurável?**

Impacto social e educacional: contato de quase 600 estudantes e professores da rede pública com eletrônica e programação, muitos pela primeira vez. Houve também ampliação da presença e do reconhecimento do IFC em municípios da região e fora do estado. Não foram localizados indicadores econômicos ou ambientais.

**O projeto gerou aprendizado ou formação adicional para os estudantes envolvidos?**

Sim. Os bolsistas atuaram no projeto, montagem e apresentação dos robôs e participaram da produção e apresentação de artigos científicos em congressos, formando dentro do campus pessoal qualificado para a prática extensionista.

---

## 5. Análise crítica do grupo

> Esta seção é a opinião do grupo. O texto abaixo é um exemplo do tipo de análise esperada — cada grupo deve escrever a sua.

**Qual é a opinião do grupo sobre o projeto desenvolvido?**

Consideramos o projeto bem construído e honesto nos seus resultados: define metas numéricas claras, cumpre todas e documenta publicamente o que fez. O mais interessante, na nossa leitura, é que a decisão técnica central — usar hardware livre em vez de kits proprietários — é o que viabiliza o alcance social do projeto. Barateando o robô e permitindo montá-lo no campus, a equipe conseguiu levar a oficina a seis municípios com orçamento de edital interno.

**Pontos fortes e possíveis melhorias**

| Pontos fortes | Pontos a melhorar |
|---|---|
| Metas mensuráveis, todas atingidas e a maioria superada em menos tempo que o previsto | Oficinas de 2 a 4 horas dão um primeiro contato, mas dificilmente sustentam aprendizado de longo prazo sem continuidade |
| Hardware livre: baixo custo e replicabilidade pelas escolas | Dependência de bolsas e editais internos torna a continuidade sensível a cortes orçamentários |
| Combinação de teoria e prática em formato compatível com a rotina escolar | Indicadores apresentados são apenas quantitativos: medem alcance, não aprendizado |
| Formação de professores, que multiplica o efeito para além do dia da oficina | Não há registro de acompanhamento das escolas após a oficina |

**Sugestões:** aplicar instrumento de avaliação de aprendizagem antes e depois da oficina; criar trilha de continuidade (empréstimo de kits às escolas, clube de robótica, acompanhamento remoto); ampliar a frente de formação de professores, que tem o maior efeito multiplicador por participante.

**Que aprendizados esse projeto trouxe para a compreensão do grupo sobre o papel da extensão na formação em exatas?**

O caso mostra que a extensão não é apenas "divulgar ciência", mas uma via de mão dupla que também qualifica o estudante de engenharia em comunicação, planejamento e trabalho em equipe — competências pouco exercitadas em disciplinas técnicas tradicionais. Aprendemos também que alcance e aprendizado são coisas diferentes: um projeto pode atingir centenas de pessoas sem conseguir demonstrar o que elas levaram da experiência.

---

## 6. Registro das fontes consultadas

| Nº | Referência (ABNT) | Tipo de fonte |
|---|---|---|
| 1 | SARAIVA, I. Z.; SILVA, I. I.; ANTONELLO, R.; OLIVEIRA, R. G.; NEVES, R. C.; BECKER, R. M.; LACERDA, M. S.; SANTOS, L. G. M.; SCHEURICH, J. P.; TAVARES, T.; OUVERNEY, M. A. *Extensão Tecnológica e hardware livre: resultados do projeto de robótica pedagógica com Arduino do IFC-Campus Luzerna nas Escolas Públicas do Meio-Oeste Catarinense.* In: Anais do 35º Seminário de Extensão Universitária da Região Sul (SEURS) — Área temática: Tecnologia e Produção. Foz do Iguaçu: Proex/UNILA, 2017. p. 168-173. ISSN 1983-6554. Disponível em: https://dspace.unila.edu.br/items/16953545-5acf-47ea-a59f-f7a9d3e263e2. Acesso em: 13 ago. 2026. | Evento / congresso de extensão (via repositório institucional) |
| 2 | ANTONELLO, R.; SILVA, R.; SARAIVA, I. Z. *Sobre tempestades cerebrais e hardware livre: resultados do projeto de Robótica Pedagógica com Arduino do IFC Campus Luzerna.* Mostra Nacional de Iniciação Científica e Tecnológica Interdisciplinar, 2017. | Evento científico — usada para conferir os números e identificar o edital de financiamento |

**Obras citadas pelo próprio projeto** (não consultadas diretamente pelo grupo): MONK, S. *30 Projetos com Arduino.* 2. ed. Porto Alegre: Bookman, 2014. · JEZINE, E. *As Práticas Curriculares e a Extensão Universitária.* 2º Congresso Brasileiro de Extensão Universitária, Belo Horizonte, 2004.

> **Observação metodológica:** as duas fontes usadas pertencem à mesma categoria do roteiro (eventos e congressos) e são dos mesmos autores, o que significa que todos os dados vêm da própria equipe do projeto. Uma pesquisa mais robusta deveria acrescentar uma categoria diferente — o site institucional do IFC Campus Luzerna, para verificar se o projeto teve continuidade após 2017, ou contato direto com a coordenação.

## 7. Arquivos gerados para entrega no SIGAA

| Arquivo | Uso |
|---|---|
| [`roteiro_preenchido_arduino.pdf`](./roteiro_preenchido_arduino.pdf) | Exemplo de roteiro preenchido, mostrando o nível de detalhe esperado |
| [`apresentacao_arduino_ifc_luzerna.pdf`](./apresentacao_arduino_ifc_luzerna.pdf) | Exemplo de apresentação montada a partir desse roteiro |

---

