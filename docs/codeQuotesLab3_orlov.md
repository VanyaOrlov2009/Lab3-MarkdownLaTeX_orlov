## Inline-код

Чтобы создать коммит, выполните команду `git commit -m "Initial commit"`, а чтобы отправить его на сервер, используйте `git push -u origin main`.

## Блок кода с указанием языка

```csharp
Console.Write("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.Write("Введите второе число: ");
double number2 = Convert.ToDouble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"Результат: {sum}");
```

## Блок кода без указания языка

```
git status
git add .
git commit -m "Add file"
git push
```

### Обычная цитата

> Git - это распределённая система контроля версий, созданная Линусом Торвальдсом для разработки ядра Linux.

### Вложенная цитата

> Система контроля версий позволяет отслеживать изменения файлов.
>
> > Благодаря этому можно вернуться к любой предыдущей версии проекта.