# Com base nos resultados obtidos durante a execução no notebook, a resposta correta à primeira pergunta da seção 9.5.7 é:

Os dados de entrada (X) e saída (Y) foram corretamente processados e estruturados como tensores, com cada sequência convertida para o formato inteiro (torch.int32). Além disso, o pré-processamento ajustou as sequências para que tenham comprimentos válidos e consistentes, o que é crucial para o treinamento do modelo de tradução automática. Esse tratamento garante que os dados estejam prontos para serem utilizados na etapa de aprendizado da máquina.

## Justificativa: 

Os resultados exibidos no notebook mostram claramente que o processamento dos dados foi bem-sucedido, apresentando sequências organizadas e adequadamente padronizadas para o treinamento, o que confirma que os procedimentos aplicados estão corretos.

# A resposta correta à segunda pergunta da seção 9.5.7 é:

O pré-processamento dos dados realizado no código foi eficaz porque lidou de forma adequada com o texto, substituindo espaços não quebráveis, convertendo todas as letras para minúsculas e adicionando espaços entre palavras e sinais de pontuação. Esses passos são essenciais em qualquer sistema de tradução automática, pois garantem que o texto fique limpo e bem estruturado, o que melhora significativamente a qualidade da tradução gerada pelo modelo.

## Justificativas com Referências:

Seção de Pré-processamento (Célula de Código 5): A função preprocess_nmt() realiza ajustes simples, mas essenciais no texto, como a padronização de espaços e a formatação dos caracteres. Esses ajustes tornam os dados mais consistentes e evitam problemas que poderiam comprometer o desempenho do modelo.

Referência Externa: Estudos sobre Processamento de Linguagem Natural (NLP) destacam que um bom pré-processamento é um passo crucial para o sucesso em tarefas de tradução automática. Ele ajuda a reduzir ambiguidades e inconsistências que podem dificultar o aprendizado do modelo (Fonte: Jurafsky, D., & Martin, J. H. (2021). Speech and Language Processing).