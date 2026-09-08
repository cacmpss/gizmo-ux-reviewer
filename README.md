# Gizmo UX Reviewer

Skill reutilizável para análises e recomendações de UX fundamentadas em fontes confiáveis. Define uma hierarquia entre regras do produto, Design Systems, documentação de plataforma, acessibilidade, pesquisas de UX e literatura profissional.

Compatível com Codex e Claude Code por usar o formato aberto `SKILL.md`.

## Instalação no Claude Code

Clone o repositório na pasta de skills pessoais:

```bash
git clone https://github.com/cacmpss/gizmo-ux-reviewer.git ~/.claude/skills/gizmo-ux-reviewer
```

O Claude Code pode ativar a skill automaticamente quando o pedido corresponder à descrição. Para invocá-la diretamente, use:

```text
/gizmo-ux-reviewer
```

Para disponibilizá-la apenas em um projeto, clone em:

```text
<projeto>/.claude/skills/gizmo-ux-reviewer
```

## Instalação no Codex

Clone o repositório na pasta pessoal de skills:

```bash
git clone https://github.com/cacmpss/gizmo-ux-reviewer.git ~/.codex/skills/gizmo-ux-reviewer
```

Depois, invoque a skill como `$gizmo-ux-reviewer` ou deixe o Codex selecioná-la automaticamente em tarefas compatíveis.

## Atualização

Dentro da pasta instalada, execute:

```bash
git pull
```

## Estrutura

```text
gizmo-ux-reviewer/
├── SKILL.md
└── agents/
    └── openai.yaml
```

`SKILL.md` contém as instruções portáveis. `agents/openai.yaml` fornece metadados adicionais para o Codex e pode ser ignorado pelo Claude Code.

## Referências de compatibilidade

- [Skills no Claude Code](https://code.claude.com/docs/en/slash-commands)
- [Agent Skills](https://agentskills.io/)
