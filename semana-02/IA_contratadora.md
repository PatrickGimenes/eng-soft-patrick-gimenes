# Análise de Riscos das Abordagens

Antes de tomar a decisão, vamos apontar os riscos de cada escolha.

---

## Human-in-the-loop

Ao adicionar um ser humano à equação, a ferramenta acaba perdendo parte do seu principal diferencial, que é automatizar todo o processo de contratação.

Além disso, ao gerar retrabalho na revisão dos últimos 20% dos candidatos - que, em uma vaga para desenvolvedor em uma empresa de grande porte, podem chegar a 3000 aplicações por vaga (referência: https://newsletter.pragmaticengineer.com/p/state-of-the-tech-market-in-2025-hiring-managers) - isso resultaria em aproximadamente 600 perfis para reanálise, além dos candidatos já selecionados pela IA.

Esse retrabalho pode afastar grandes empresas, gerar perda de competitividade e favorecer concorrentes. Ainda assim, existe o risco de candidatos serem desclassificados por viés.

---

## Toolkit de Explicabilidade (XAI)

Apesar de oferecer maior transparência e permitir que os clientes entendam os motivos das rejeições, essa abordagem pode gerar processos judiciais e custos adicionais.

Além disso, ao expor regras de negócio, concorrentes podem utilizar o sistema como benchmark, ganhando vantagem competitiva. Também existe o risco de hacktivismo, com tentativas de manipulação para criar uma imagem negativa da empresa, afetando sua reputação.

Por outro lado, a adoção dessa solução demonstra maior maturidade tecnológica e adiciona uma camada extra de segurança e governança.

---

## Auditoria de Dados

Ao reconhecer falhas no dataset, a software house demonstra um nível relevante de maturidade. Apesar do atraso necessário para corrigir os dados, essa abordagem pode resultar em um produto mais robusto e confiável.

Caso um concorrente lance uma solução semelhante durante esse período, existe o risco de perda de mercado. No entanto, a auditoria permite evoluir para uma versão mais estável e menos suscetível a falhas críticas.

---

## Riscos Legais e Financeiros

O custo de uma infração pode chegar a até 2% do faturamento da empresa, limitado a R$ 50 milhões por infração. Em empresas de grande porte, esse teto pode ser facilmente atingido.

Além da multa, múltiplos usuários podem entrar com ações judiciais, ampliando significativamente os custos.

Caso seja comprovado que candidatos foram recusados por motivos discriminatórios (raciais, homofóbicos, etc.), podem ocorrer:

- Ações judiciais individuais (danos morais)
- Ações coletivas (Ministério Público)
- Sanções por discriminação racial (Lei nº 7.716/1989)

Além disso, há o impacto reputacional, que pode gerar forte repercussão negativa na mídia e consequente perda de valor de mercado.

---

## Conclusão

A solução mais adequada, neste caso, seria revisar o dataset utilizado no treinamento para mitigar vieses na tomada de decisão da IA.

Além disso, é recomendável implementar um toolkit de explicabilidade, permitindo maior transparência e oferecendo suporte em eventuais disputas legais.
