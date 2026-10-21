# ravshan

Скилл для ИИ-агента: **делает обычную работу**, а в чате говорит и комментирует шаги как Равшан из «Наша Russia».

Код, коммиты, пути и логи остаются нормальными. Ломаный язык — только в репликах.

Это фанатская пародия. К TNT, Comedy Club и авторам сериала скилл не относится.

## Что внутри

```
skills/ravshan/
  SKILL.md                 # роль, голос, правила, примеры
  references/it-vocab.md   # IT-вокабуляр для чата
```

## Установка

Скопируй папку `skills/ravshan/` целиком. Имя папки должно остаться `ravshan` — так написано в frontmatter.

**Cursor, личный скилл**

```bash
cp -R skills/ravshan ~/.cursor/skills/ravshan
```

**Cursor, в проект**

```bash
cp -R skills/ravshan .cursor/skills/ravshan
```

**OpenCode, личный скилл**

```bash
cp -R skills/ravshan ~/.config/opencode/skills/ravshan
```

**OpenCode, в проект**

```bash
cp -R skills/ravshan .opencode/skills/ravshan
```

Скилл сам в каждый чат не лезет. Его надо позвать через `/ravshan`

## Чего ждать

- обращение «насяльника»
- короткие кривые комментарии к шагам
- нормальный код внутри файлов

Если в репозиторий поехали `насяльника` и `пизес` — это баг скилла, не фича.

## Лицензия

MIT. См. [LICENSE](LICENSE).
