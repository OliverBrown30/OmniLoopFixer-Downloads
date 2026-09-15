# Встановлення через Antigravity

На Mac відкрийте Antigravity і вставте запит нижче. Підтвердження першого запуску macOS може вимагати виконати вручну.

```text
Допоможи встановити OmniLoopFixer на цей Mac із готового інсталятора:
https://github.com/OliverBrown30/OmniLoopFixer-Downloads/releases/tag/v0.1.0-test

Це тестова збірка без Developer ID і нотаризації Apple.
Перевір Apple Silicon (arm64) та macOS 15 або новішу. Якщо ця сесія
працює через Rosetta, перевір фізичну архітектуру Mac перед висновком.

Завантаж саме OmniLoopFixer-AppleSilicon-TEST-unnotarized.dmg з Assets,
а не Source code.zip. Пряме посилання:
https://github.com/OliverBrown30/OmniLoopFixer-Downloads/releases/download/v0.1.0-test/OmniLoopFixer-AppleSilicon-TEST-unnotarized.dmg

Перевір SHA-256 файла; очікувана сума:
af3dcff2649e8392edb1de74a7fd1f651e77a07c58a706950bad3cb5698ee95c
Якщо сума інша — зупинись. Перевір DMG через hdiutil verify.
Змонтуй DMG лише для читання, визнач шлях тому з результату hdiutil,
знайди OmniLoopFixer.app і перевір цілісність його підпису через
codesign --verify --deep --strict. Ad-hoc підпис не є підписом Apple.

Скопіюй програму в ~/Applications зі збереженням структури app bundle
(наприклад, ditto). Якщо OmniLoopFixer.app уже існує, не перезаписуй
її автоматично: спочатку узгодь заміну. Не встановлюй окремо Python,
Homebrew чи FFmpeg — усе потрібне вже всередині. Відмонтуй DMG.

Допоможи запустити встановлену програму. Якщо macOS блокує невідомого
розробника, покажи мені ручний шлях System Settings → Privacy & Security
→ Open Anyway для цієї конкретної програми. Не натискай підтвердження
без мене, не вимикай Gatekeeper, не використовуй spctl --master-disable
або xattr для обходу захисту. Якщо повідомлено про пошкодження чи malware,
зупинись та покажи точний текст помилки.

Після відкриття поясни: вибрати/перетягнути відео → Auto Cut + save x5.
Corrected loop і Preview x5 зберігаються окремо, без звуку.
Не надсилай мої відео в інтернет. Повідом, чи програма справді відкрилася,
та які кроки ще потребують моєї участі.
```
