<!-- agent-board:start -->
## Agent Board

- Все задачи ведутся через `gh-issues` / Agent Board.
- Перед работой: `board init` или `board bootstrap-repo --repo allgrit/snake-bros`.
- Перед началом, перед коммитом и перед финальным ответом: `board audit --repo allgrit/snake-bros --local`.
- Новые задачи создавать только через `board create allgrit/snake-bros "...title..." "...body..." <Priority> <Effort> <Type>`.
- Для каждой задачи обязательны `Repository`, `Status`, `Priority`, `Effort`, `Type`.
- Работу начинать через `board pick N --repo allgrit/snake-bros` и закрывать через `board done N "...итог..." --repo allgrit/snake-bros`.
- Reusable library/generator/CLI/skill work заводить в repo-владельце; consumer repo получает только integration/e2e scope.
<!-- agent-board:end -->
