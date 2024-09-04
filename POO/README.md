# 🚀 Trilha Java Básico / Luciano Aparecido de Siqueira

## 👤 Autor
- [Luciano](https://github.com/siqueira1989)

## 🏆 Desafio de Programação Orientada a Objetos (POO)

### 🛠️ Modelagem e Diagramação de um Componente iPhone

Este desafio tem como objetivo desenvolver a modelagem e diagramação UML do componente iPhone, abordando suas funcionalidades essenciais como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### 🎯 Contexto
Com base no vídeo de lançamento do iPhone de 2007 (link abaixo), elabore a diagramação das classes e interfaces utilizando uma ferramenta UML de sua preferência. Após a diagramação, implemente as classes e interfaces no formato de arquivos `.java`.

- [📺 Lançamento iPhone 2007](https://www.youtube.com/watch?v=9ou608QQRq8)
  - ⏱️ Minutos relevantes: 00:15 até 00:55

#### 📋 Funcionalidades a Modelar
1. **🎵 Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **📞 Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **🌐 Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### 🎯 Objetivo do Desafio
1. Desenvolver um diagrama UML que represente as funcionalidades descritas acima.
2. Implementar as classes e interfaces correspondentes em Java (Opcional).

### 🖼️ Exemplo de Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
