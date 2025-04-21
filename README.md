# 📑 README — Tela Inicial da Loja de Jogos (Angular)

## 📌 Descrição

Este projeto contém a implementação da **tela inicial de uma loja de jogos**, desenvolvido com **Angular** e **TypeScript**, como parte da atividade avaliativa da disciplina **CTMSP_DDF_QO_FULLST_242T12_IAPIS_QUA.459.022**.

---

## 🛠️ Tecnologias Utilizadas

- **Angular**
- **TypeScript**
- **HTML5**
- **CSS3**

---

## 📦 Requisitos para executar o projeto

Antes de iniciar, é necessário ter instalado em sua máquina:

- **Node.js** 👉 [https://nodejs.org/](https://nodejs.org/)
- **Angular CLI** 👉 para instalar:
```bash
npm install -g @angular/cli
```

---

## 📥 Como executar o projeto

1️⃣ Clone este repositório:
```bash
git clone https://github.com/lucasm9140/ProjetoAngularSiteJogos.git
```

2️⃣ Acesse a pasta do projeto:
```bash
cd ProjetoAngularSiteJogos
```

3️⃣ Instale as dependências:
```bash
npm install
```

4️⃣ Rode o projeto:
```bash
ng serve
```

5️⃣ Acesse no navegador:
```
http://localhost:4200/
```

---

## 📚 Sobre TypeScript (resumo)

**TypeScript** é uma linguagem baseada em JavaScript que adiciona:

- Tipagem estática
- Suporte a programação orientada a objetos (classes, interfaces, herança)
- Detecção de erros em tempo de compilação

### 📌 Exemplo de classe em TypeScript:
```typescript
class Jogo {
  titulo: string;
  preco: number;

  constructor(titulo: string, preco: number) {
    this.titulo = titulo;
    this.preco = preco;
  }

  exibirInformacoes(): void {
    console.log(`Jogo: ${this.titulo}, Preço: R$ ${this.preco}`);
  }
}
```

---

## 📄 Licença

Projeto acadêmico para fins educacionais.
