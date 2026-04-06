# Спецификация данных товара

## Входные данные от пользователя
- `query`: string (обязательное)
- `weights`: object с полями `price`, `delivery`, `rating` (опционально, по умолчанию 0.5, 0.3, 0.2)

## Выходные данные API (JSON)
```json
{
  "query": "наушники Sony",
  "results": [
    {
      "title": "Наушники Sony WH-1000XM5",
      "marketplace": "Ozon",
      "price": 24990,
      "delivery_days": 2,
      "seller_rating": 4.9,
      "url": "https://ozon.ru/...",
      "benefit_index": 0.873
    }
  ]
}
