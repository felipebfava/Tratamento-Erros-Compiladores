### Alunos
Felipe Biava Favarin

Matheus Alves Bueno Machado

### Objetivos
Grave um vídeo (YouTube não listado) de até 5 minutos explicando (com a sua voz e com os recursos que julgar úteis), todos os erros que podem ocorrer durante uma compilação e as estratégias de tratamento e recuperação de tais erros.

### Metodologia
Usaremos a Linguagem C, por ser uma linguagem Compilada para mostrar os erros que podem ser causados

#### Estrutura dos Arquivos
Os arquivos estão organizados como:

    C:.\trataErro

        ├───Erros_Tipagem

        ├───Erro_Lexico

        ├───Erro_Linkedicao

        ├───Erro_Semantico

        ├───Erro_Sintatico

        ├───Erro_Tempo_Compilacao

        ├───Warnings_Avisos

        └───README.md

### Resumo Geral

| Tipo de erro | Fase |
| --- | --- |
| Léxico | Análise léxica |
| Sintático | Parsing |
| Semântico | Análise semântica |
| Tipagem | Semântica |
| Linkedição | Linker |
| Runtime detectável | Otimização/análise |
| Warnings | Diversas fases |

### Conclusão
Os erros de compilação são essenciais para garantir a correção, segurança e confiabilidade dos programas. Cada fase da compilação possui mecanismos específicos para identificar problemas relacionados à estrutura, significado e organização do código.

Além de detectar erros, compiladores modernos procuram recuperar-se deles para continuar a análise do programa e fornecer mensagens mais completas ao desenvolvedor. Isso aumenta significativamente a produtividade e facilita a identificação de problemas no desenvolvimento de software.
