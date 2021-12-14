---
id: 5900f4031000cf542c50ff16
title: 'Завдання 151. Аркуші стандартних розмірів: середня очікувана кількість'
challengeType: 5
forumTopicId: 301782
dashedName: problem-151-paper-sheets-of-standard-sizes-an-expected-value-problem
---

# --description--

Щотижня друкарня друкує 16 партій (завдань), і для кожної партії потрібен аркуш спеціального кольоропробного паперу формату A5.

Щоранку в понеділок бригадир відкриває новий конверт, який містить великий аркуш спеціального паперу розміром A1.

Він ділить його навпіл, таким чином отримуючи два аркуші розміром А2. Потім він розрізає один з них навпіл, щоб отримати два аркуші формату А3 і так далі, поки не отримає аркуш розміром А5, необхідний для першої партії тижня.

Усі невикористані аркуші кладуть назад у конверт.

<img class="img-responsive center-block" alt="Аркуш розміром A1 може бути поділений на аркуші форматом: A2, A3, A4 та два аркуші форматом A5" src="https://cdn.freecodecamp.org/curriculum/project-euler/paper-sheets-of-standard-sizes-an-expected-value-problem.png" style="background-color: white; padding: 10px;" />

На початку кожної наступної партії він навмання бере один аркуш паперу з конверта. Якщо він виявляється розміром А5, то використовує його. Якщо ж більший, то він повторює процедуру «розрізання навпіл», поки не отримає те, що йому потрібно, а решту аркушів повертає назад до конверта.

За виключенням першої та останньої партії, знайдіть очікувану кількість разів (протягом кожного тижня), коли бригадир знайде в конверті один аркуш.

Дайте відповідь, заокруглену до шести знаків після коми, використовуючи формат `x.xxxxxx`.

# --hints--

`expectedValueProblem()` має повернути `0.464399`.

```js
assert.strictEqual(expectedValueProblem(), 0.464399);
```

# --seed--

## --seed-contents--

```js
function expectedValueProblem() {

  return true;
}

expectedValueProblem();
```

# --solutions--

```js
// solution required
```