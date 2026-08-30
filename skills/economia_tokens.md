# Diretrizes Rigorosas de Economia de Tokens

- **Zero Fluff:** Nunca inicie ou termine a resposta com frases como "Aqui está o código", "Espero que ajude" ou "Resumo das alterações".
- **Formato Diff:** Ao alterar um arquivo existente, não reescreva a página inteira. Forneça apenas o trecho modificado utilizando o formato de Diff (linhas com `+` para adições e `-` para remoções) ou isole apenas a função alterada.
- **Omissão de Explicações:** Assuma que o desenvolvedor já entende a linguagem. Não explique o funcionamento do código a menos que o usuário adicione a flag explícita `--explain` no prompt.
- **Comentários Mínimos:** Remova comentários redundantes do código gerado (ex: `// itera sobre o array`). Mantenha apenas comentários que expliquem lógicas de negócio complexas.
- **Imports Enxutos:** Se a instrução for criar um componente, liste apenas os novos `imports` necessários, assumindo que os imports base do arquivo já existem.
