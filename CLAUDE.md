<!-- lex: собран из ~/.claude/codex/manifest/git-talks-CLAUDE.md.yaml. Правь фрагменты в ~/.claude/codex/frag и запусти `lex build --codex ~/.claude/codex`; правку прямо в этом файле перенеси во фрагменты: `lex absorb --codex ~/.claude/codex <этот файл>` -->
# talks

Доклады пользователя: папка на доклад (`index.html` — слайды, `slides.pdf`), список — `README.md`.

- Репо публичное, `main` из корня публикует GitHub Pages (https://aiseeq.github.io/talks/): push — публикация под именем пользователя, поэтому он идёт после его «да» (общий CLAUDE.md, «Люди: вопросы, тексты, просьбы»). Текст слайдов и его push — по скиллу `write-article`: прочитать /home/aisee/git/life/.claude/skills/write-article/SKILL.md (скилл живёт в life).
  Зачем: текст слайдов не уходит в публичный доступ под именем пользователя без его «да»
- Сборки и гейта нет (`.graft.yaml` нет): коммит — обычным git в `main`. Перед push открыть `index.html` в браузере и проверить, что слайды листаются, а PDF совпадает с HTML.
  Зачем: сломанные слайды и PDF, разошедшийся с HTML, не попадают в публичный доступ: гейта, который бы их поймал, нет
