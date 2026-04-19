# RA Language Support

Supporto VS Code per i file `.ra`.

## Include

- syntax highlighting basato sulle regole del lexer/parser
- auto-closing per parentesi, graffe, quadre e apici
- completamenti per keyword, tipi e blocchi
- snippet per classi, struct, trait, interface, enum, funzioni, controllo di flusso, `try/catch/finally`, `retry`, `extend`, `impl`

## Regole coperte

Keyword principali: abstract, and, as, break, case, catch, class, const, continue, default, del, delay, do, elif, else, enum, extend, false, final, finally, fn, for, goto, if, impl, in, interface, let, nameof, not, not in, null, or, override, pass, pub, ret, retry, self, static, step, struct, super, switch, times, to, trait, true, try, typeof, var, while, with, yield.

Tipi built-in: int, number, long, float, double, uint, ulong, short, ushort, int128, uint128, decimal, byte, bool, string, char, void, object, any.

## Avvio rapido

1. Apri la cartella in VS Code
2. Premi `F5`
3. Apri un file `.ra`

## Note

La grammatica evidenzia anche:
- commenti `//`, `#`, `---`, `/* */`, `<!-- -->`
- stringhe con apici singoli, doppi e backtick
- interpolazione `$Ellipsis`
- numeri interi e floating con prefissi e suffissi
- operatori e punteggiatura del linguaggio
