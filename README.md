# sse-ws-anim

[![Build status](https://ci.appveyor.com/api/projects/status/i151i5juc1vftfia?svg=true)](https://ci.appveyor.com/project/AACMKT/ahj-anim)

[Ссылка на публикацию приложения на GitHub Pages](https://aacmkt.github.io/ahj-anim/)
---

### Описание

Реализован виджет "раскрытия" текстового окна при нажатии на кнопку.

Особенности:

- функционал виджета вынесен в отдельный класс
- класс содержит два метода для анимации: с использованием рекурсивного вызова `RequestAnimationFrame` и с использованием CSS классов с атрибутами `transition`.
- добавление/снятие внутренних отсупов и границ текстового блока контролируются при помощи библиотеки `element-resize-event`.
  

---

Покрытие тестами не осуществлялось.
