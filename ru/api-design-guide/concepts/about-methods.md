# Методы в API

Для управления ресурсами в [API Яндекс.Облака](https://github.com/yandex-cloud/cloudapi) определен набор методов. Каждому gRPC-методу ставится в соответствие HTTP-глагол. Например, методу `List` соответствует глагол `GET`,  а методу `Create` — глагол `POST`. Соответствия HTTP-запросам задаются в описании методов, в аннотации [google.api.http](https://github.com/googleapis/googleapis/blob/master/google/api/http.proto).

В API есть два набора методов: 

[!INCLUDE [method-sets](../_includes/method-sets.md)]

> [!NOTE]
>
> Справочники gRPC API находятся в разработке и будут опубликованы в ближайшее время.

