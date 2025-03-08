[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Oswald&weight=500&size=30&pause=1000&color=195671FF&width=435&lines=Seja+Bem+Vindo+Bora+Aprender+C%2B%2B)](https://git.io/typing-svg)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Oswald&weight=500&size=30&pause=1000&color=195671FF&center=true&vCenter=true&width=435&lines=Olá+Mundo!+em+C%2B%2B)](https://git.io/typing-svg)

![cpp-gif](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZTBtM2U4eXUyN2tpbWpoYmpzdWVyZWc1ZTE1YWlhbmRqMzY2ZWFkbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/FoVzfcqCDSb7zCynOp/giphy.gif)

Este é o seu primeiro programa em C++! Ele exibe a mensagem "Olá Mundo!" no console. 🎉

## 💻 Código

```
#include <iostream>  // 📚 Inclui a biblioteca iostream para entrada e saída de dados

int main() {
    std::cout << "Olá Mundo!\n";  // 💬 Exibe a mensagem "Olá Mundo!" no console

    return 0;  // ✅ Indica que o programa foi executado com sucesso
}
```

### 🔍 Explicação do Código:
1️⃣ **`#include <iostream>`** 📚  
   - Importa a biblioteca `iostream`, permitindo entrada e saída de dados.  

2️⃣ **`int main() { ... }`** 🔑  
   - Define a função principal do programa.  
   - Todo programa C++ começa sua execução a partir dessa função.  

3️⃣ **`std::cout << "Olá Mundo!\n";`** 💬  
   - Exibe a mensagem `"Olá Mundo!"` no console.  
   - `std::cout`: Objeto de saída padrão em C++.  
   - `<<`: Operador de inserção, que envia o texto para `std::cout`.  
   - `\n`: Quebra de linha (equivalente a pressionar "Enter").  



4️⃣ **`return 0;`** ✅  
   - O comando `return` finaliza a execução da função `main()`.  
   - Em C++, a função `main()` deve retornar um valor inteiro (`int`), que informa ao sistema operacional se o programa foi concluído com sucesso ou se ocorreu algum erro.  
   - **`return 0;`** indica que o programa foi executado corretamente, sem erros.  
   - Caso o programa falhe e precise indicar um erro, pode-se retornar um valor diferente de zero, como `return 1;`, `return -1;` ou outro código específico.  
   - Exemplo prático:  
     ```cpp
     int main() {
         if (erro_ocorreu) {
             return 1;  // 🔴 Código de erro (o programa falhou)
         }
         return 0;  // ✅ Programa finalizado com sucesso
     }
     ```
   - Esse retorno pode ser útil em programas maiores, especialmente quando são usados em **scripts automáticos**, onde um código de erro pode ser usado para identificar problemas.  




## 🚀 Compilação e Execução

1. **Salve o código:** Salve o arquivo com o nome `hello_world.cpp` (ou, opcionalmente, `hello_world.c++`). 💾

   **Observação:**  
   Embora a extensão `.cpp` seja a mais comum para arquivos de código C++, outras extensões como `.cc`, `.cxx`, ou até mesmo `.c` (para código C) podem ser usadas, dependendo do estilo do projeto ou das preferências do desenvolvedor. `.h` é geralmente utilizada para arquivos de cabeçalho em C e C++.

2. **Compile:** Use o compilador `g++` para transformar o código em um executável. ⚙️

    ```
    g++ hello_world.cpp -o hello_world
    ```

4.  **Execute:** Execute o programa! 🏃‍♂️

    ```
    ./hello_world
    ```

    Você verá a mensagem "Olá Mundo!" no seu console. 🌍

## 💡 Dicas

*   **`\n` vs `std::endl`:**
    *   ✅ Use `\n` na maioria dos casos: É mais rápido e eficiente.
    *   ⚠️ Use `std::endl` apenas quando precisar forçar a saída imediata (ex: para fins de *debug*).
*   **Comentários:**
    *   `//` Para comentar uma única linha.
    *   `/* ... */` Para comentar múltiplas linhas.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma *pull request*. 😊
