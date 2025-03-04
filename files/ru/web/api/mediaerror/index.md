---
title: MediaError
slug: Web/API/MediaError
---

{{APIRef("HTML DOM")}}

Интерфейс `MediaError` представляет собой ошибку, возникшую при обработке мультимедиа в HTML-элементе мультимедиа на основе {{domxref ("HTMLMediaElement")}}, например {{HTMLElement ("audio")}} или {{HTMLElement ("video")}}.

Объект `MediaError` описывает ошибку в общих чертах, используя числовой код, классифицирующий тип ошибки, и сообщение, которое предоставляет конкретную диагностику о том, что пошло не так.

## Свойства

_Этот интерфейс не наследует никаких свойств._

- {{domxref("MediaError.code")}}
  - : Число, которое представляет общий тип ошибки, которая произошла, следующим образом: {{page("/ru/docs/Web/API/MediaError/code", "Константы кода ошибки носителя")}}
- {{domxref("MediaError.message")}}
  - : Объект {{domxref("DOMString")}} содержит читаемую человеком строку, которая предоставляет конкретную диагностическую информацию, чтобы помочь читателю понять возникшее состояние ошибки; в частности, это не просто краткое изложение того, что означает Код ошибки, но фактическая диагностическая информация, помогающая понять, что именно пошло не так. Этот текст и его формат не определяются спецификацией и будут варьироваться от одного {{Glossary("user agent")}} к другому. Если диагностика недоступна или объяснение не может быть предоставлено, это значение является пустой строкой (`""`).

## Методы

_Этот интерфейс не реализует и не наследует никаких методов и не имеет своих собственных._

## Спецификации

{{Specifications}}

## Совместимость браузера

{{Compat}}

## Изучите также

- {{domxref("HTMLMediaElement.error")}}
