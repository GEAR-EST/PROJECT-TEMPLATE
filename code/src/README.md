> *OBS: Este arquivo (code/README.md) deve ser excluído, ele serve apenas como guia para entender como é organizado o este diretório (/code). Então mesmo que não tenha a seguir coisas em itálico, este arquivo por completo deve ser excluído futuramente*

---

Este diretório é destinado aos arquivos de código-fonte do projeto.

O PlatformIO irá compilar automaticamente os arquivos-fonte deste diretório e vinculá-los ao firmware executável no microcontrolador.

O arquivo principal da sua aplicação (por exemplo, `main.cpp`) deve ser colocado aqui.

**Exemplo (`src/main.cpp`):**

```cpp
#include <Arduino.h>

void setup() {
  // O seu código de inicialização vai aqui, para ser executado uma vez:
}

void loop() {
  // O seu código principal vai aqui, para ser executado repetidamente:
}
```