# Maintenance Notes

- Phone crossword pages have two input modes:
  - Page keys: custom QWERTY/number keypad is shown and native keyboard is suppressed.
  - Phone keys: native keyboard is allowed and the custom keypad collapses to a single `Page keys` switch.
- When adding Supabase leaderboard/comments, review the phone-page input mode around `nativeKeyboard`, `updateNativeInputs`, and `renderKeypad` before wiring submit controls near the keypad/timer area.
