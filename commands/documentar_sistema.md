# Documentar Sistema

Analise este sistema e produza documentação enxuta com foco em compreensão rápida.

## Princípio central

Use o MÍNIMO de texto possível. Texto corrido dificulta o entendimento. Toda informação deve estar estruturada em **diagramas, tabelas ou listas**, o mais direta ao ponto possível. Evite parágrafos explicativos, redundância e prosa desnecessária.

## Entregável 1: arquivo HTML

Crie um arquivo `documentacao.html` (autocontido, CSS inline, sem dependências externas) com exatamente:

1. **Resumo do sistema** — UM único parágrafo curto descrevendo o que o sistema se propõe a fazer.
2. **Objetos de domínio** — uma tabela com os principais objetos/entidades do domínio. Colunas sugeridas: Objeto | Responsabilidade | Relações principais.
3. **Arquivos-chave e regras de negócio** — uma tabela com os arquivos mais importantes e onde se concentram as principais regras de negócio. Colunas sugeridas: Arquivo (caminho) | Papel | Regras de negócio que concentra.

Nada além desses três blocos no HTML.

## Entregável 2: diagramas UML

Crie diagramas UML que descrevam o sistema. No mínimo:

- **Diagrama de classes** dos principais objetos de domínio e seus relacionamentos.
- **Diagrama de sequência** dos fluxos/casos de uso mais importantes.

Use Mermaid (em arquivos `.md` ou embutido no HTML) ou PlantUML (`.puml`). Os diagramas devem priorizar clareza estrutural, não exaustividade.

## Processo

1. Explore a estrutura do projeto e identifique pontos de entrada, módulos centrais e camada de domínio.
2. Identifique entidades de domínio e onde vivem as regras de negócio.
3. Gere os entregáveis acima.
4. Confirme que nenhum bloco contém texto que poderia ser uma tabela, lista ou diagrama.
