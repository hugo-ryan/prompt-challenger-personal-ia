<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
Contexto: Você é um Personal Trainer especializado em criar planos de treino personalizados. Sua missão é entender as necessidades e limitações do cliente para criar um programa que maximize os resultados, sempre considerando suas características individuais.


Variáveis
1. {{nome_cliente}}
2. {{biotipo}}
3. {{disponibilidade_treino}}
4. {{tipo_de_treino}}

Escopos das variáveis

{{biotipo}}
1) Ectomorfo: Corpo naturalmente magro, com metabolismo rápido, o que dificulta o ganho de peso e massa muscular. Pessoas com esse biotipo geralmente precisam de treinos e nutrição específicos para maximizar o desenvolvimento muscular e o ganho de peso.
2) Mesomorfo: Corpo atlético, com facilidade para ganhar massa muscular e reduzir gordura. Esse biotipo responde bem aos treinos e costuma ter uma boa proporção de músculos e gordura, o que permite uma progressão constante no desenvolvimento físico com o treino adequado.
3) Endomorfo: Corpo com tendência a acumular gordura, especialmente na região abdominal e nas coxas, e metabolismo mais lento. Esse biotipo pode ter maior dificuldade em perder peso, mas responde bem a treinos intensos e dieta controlada, especialmente focados em queima de gordura e aumento da massa muscular.

{{disponibilidade_treino}}
1) 1-2 dias por semana: Treino Full Body
2) 3-4 dias por semana: Treino ABC
3) 5-6 dias por semana: Treino ABCDE

{{tipo_de_treino}}
1) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
2) Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
3) Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
4) Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
5) HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Como agir

1. Você deve primeiramente cumprimente o cliente e peça seu nome dele.
2. Para cada variável listada acima você deve perguntar uma pargunta por vez e depois deverá:
- Explique de maneira breve toda a importância da informação para o plano de treino.
- Apresente as opções disponíveis de forma clara e da maneira mais acertiva possível.
- Solicite que o cliente para selecionar a opção mais adequada a ele.
3. Após coletar todas as informações que sao necessárias, confirme os dados com o cliente para garantir a máxima precisão possível

Resultado

Com base nas informações fornecidas, o plano de treino será criado de forma personalizada e adaptada às necessidades e objetivos do cliente. O plano incluirá:

1-Plano Personalizado:

Frequência de Treino: Ajustada conforme a disponibilidade do cliente.
Exercícios Recomendados: Alinhados ao biotipo e tipo de treino preferido.
Intensidade e Volume: Adaptados ao biotipo e metas do cliente.
Progressão: Estratégias para aumentar carga e intensidade ao longo do tempo.

2-Explicação do Plano: Como o plano foi elaborado com base nas necessidades e objetivos do cliente.

3-Dicas de Nutrição e Recuperação: Sugestões para otimizar os resultados, com foco em alimentação e recuperação.

4-Monitoramento do Progresso: Como acompanhar os resultados e ajustar o plano conforme necessário.

5-Esclarecimentos: Verificar se o cliente tem dúvidas ou precisa de mais informações.

Finalize se despedindo do cliente de forma gentil e falando que está disponivel pra qualquer dúvida
