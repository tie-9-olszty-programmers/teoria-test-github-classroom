# teoria-test-github-classroom


# 📘 Klasy statyczne (C#)

## 🔍 Co to jest?

Klasa statyczna to taka, której **nie można zainstancjonować**, a wszystkie jej człony są statyczne.

Używamy jej, gdy nie potrzebujemy przechowywać stanu, a tylko chcemy korzystać z narzędzi, np. obliczeń.

## 🧪 Przykład:

```csharp
public static class MathHelper
{
    public static int Square(int x)
    {
        return x * x;
    }
}
