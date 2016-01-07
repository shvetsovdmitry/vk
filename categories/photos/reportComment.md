---
layout: default
title: Метод Photos.ReportComment
permalink: photos/reportComment/
comments: true
---
# Метод Photos.ReportComment
Позволяет пожаловаться на комментарий к фотографии.

Страница документации ВКонтакте [photos.reportComment](https://vk.com/dev/photos.reportComment).
## Синтаксис
``` csharp
public bool ReportComment(long ownerId, ulong commentId, ReportReason reason)
```

## Параметры
+ **ownerId** - Идентификатор владельца фотографии к которой оставлен комментарий. целое число, обязательный параметр
+ **commentId** - Идентификатор комментария. положительное число, обязательный параметр
+ **reason** - Причина жалобы:   0 — спам;  1 — детская порнография;  2 — экстремизм;  3 — насилие;  4 — пропаганда наркотиков;  5 — материал для взрослых;  6 — оскорбление.  положительное число

## Результат
После успешного выполнения возвращает 1.

## Пример
``` csharp
// Пример кода
```