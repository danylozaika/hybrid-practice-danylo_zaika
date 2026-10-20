# Заіка Данило ІПЗм-26-1 B
Мета: емпірично порівняти два підходи до розв'язання логічних задач — монолітний та гібридний

Для гібридної системи було створено такі правила:
1. Declare every integer variable and its complete domain.
2. Use [lo, hi] for an inclusive integer interval, or
   {{"values": [v1, v2, ...]}} for a finite set.
3. Put every logical condition in "constraints".
4. Use "all_different" for groups of pairwise distinct variables.
5. Use "objective": null unless optimization is explicitly required.
6. Do not introduce assumptions not stated or implied by the puzzle.
7. Use only declared variable names and allowed operators.
8. For truth-tellers and liars, use variables in [0, 1],
   where 1 means truthful and 0 means lying.
9. Encode exactly one with a sum == 1, at most one with <= 1,
   and at least one with >= 1.
10. For distinct positions, use all_different.
    Encode adjacency as abs(A - B) == 1.
11. For optimization, use:
    {{"maximize": "expression"}} or {{"minimize": "expression"}}.
12. Use only integers.
13. Don't forget commas.

Example:
A and B are distinct integers from 1 to 3. Their sum is 4.

Деякі правила мають допомагати із правильним утворенням правил. Інші ж, такі як 12 та 13 були додані для того що б усі задачі могли бути виконані без помилки під час роботи символьного розв’язувача.

## Результати

|Номер задачі|Моноліт|Гібрид|
|--------|--------|--------|
|B1|--------|--------|
|B2|--------|--------|
|B3|--------|--------|
|B4|--------|--------|
|B5|--------|--------|
