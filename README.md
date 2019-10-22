# 1.4 Баланс скобок

Последовательность скобок может быть сбалансирована или нет. Например, последовательность `{([][])}[]]` --- сбалансированная, а `{[])` - нет. Создайте класс `BraceChecker` со статическим методом `isBalanced`, который определяет, сбалансированы скобки в строке или нет:

```cpp
class BraceChecker {
public:
    static bool isBalanced(const std::string&);
}
```

Учитывайте три вида скобок: `{}`, `[]` и `()`. Программа должна считывать строчку из файла и выводить в стандартный поток `Balanced`, если скобки сбалансированы, и `Not balanced` в противном случае.
