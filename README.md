# 🗳️ URNA HTML

## Sistema de Votação Eletrônica do Grêmio Estudantil

O **URNA HTML** é um sistema de votação eletrônica desenvolvido para auxiliar na realização de eleições do Grêmio Estudantil da **Escola Professor Vicente Peixoto**.

O projeto foi desenvolvido utilizando **HTML5, CSS3 e JavaScript**, com o objetivo de criar uma experiência semelhante à utilização de uma urna eletrônica, permitindo que os estudantes realizem seus votos por meio de uma interface simples, organizada e intuitiva.

O sistema funciona localmente no computador e utiliza o **LocalStorage do navegador** para armazenar as informações das chapas e os votos registrados.

---

# 📌 Sobre o projeto

O projeto foi criado para ser utilizado em uma eleição escolar do Grêmio Estudantil.

A proposta é disponibilizar uma solução eletrônica capaz de organizar o processo de votação sem depender de um servidor externo, banco de dados online ou conexão permanente com a internet.

O sistema é dividido principalmente em duas partes:

### 🗳️ Urna de votação

Interface utilizada pelos estudantes para realizar seus votos.

### ⚙️ Painel Administrativo

Interface utilizada pelos responsáveis pela eleição para cadastrar chapas, acompanhar os resultados e administrar os dados da votação.

---

# 🎯 Objetivos

O projeto possui como principais objetivos:

- Criar uma urna eletrônica para uma eleição escolar;
- Facilitar o processo de votação dos estudantes;
- Permitir o cadastro das chapas participantes;
- Exibir informações das chapas durante a votação;
- Registrar votos válidos;
- Registrar votos nulos;
- Registrar votos em branco;
- Armazenar os dados localmente;
- Disponibilizar uma área administrativa;
- Facilitar a apuração dos resultados;
- Permitir a impressão dos resultados;
- Permitir exportação e importação das chapas;
- Criar uma experiência semelhante a uma urna eletrônica real;
- Desenvolver uma aplicação prática utilizando tecnologias web.

---

# 🏫 Informações do projeto

**Instituição:** Escola Professor Vicente Peixoto

**Projeto:** Sistema de Votação do Grêmio Estudantil

**Tipo:** Projeto escolar

**Funcionamento:** Local / Offline

**Tecnologias principais:** HTML, CSS e JavaScript

**Armazenamento:** LocalStorage

---

# 💻 Tecnologias utilizadas

## HTML5

Responsável pela estrutura das páginas do sistema, incluindo a urna de votação e o painel administrativo.

## CSS3

Responsável pela aparência visual, organização dos elementos, cores, botões, teclado numérico, painel e interface da urna.

## JavaScript

Responsável pela lógica do sistema, incluindo:

- Cadastro das chapas;
- Busca das chapas;
- Registro dos votos;
- Votos nulos;
- Votos em branco;
- Atualização da tela;
- Sons da urna;
- Apuração;
- Gerenciamento administrativo;
- Importação e exportação;
- Controle do encerramento da eleição.

## LocalStorage

O navegador é utilizado para armazenar localmente as informações da eleição.

---

# 🗳️ Funcionamento da urna

Ao abrir a urna, o eleitor encontra uma interface inspirada em uma urna eletrônica.

O eleitor deve informar o número correspondente à chapa desejada.

Após a digitação do número, o sistema procura automaticamente a chapa cadastrada.

Quando a chapa é encontrada, a urna apresenta informações como:

- Número;
- Nome;
- Foto;
- Situação do voto.

O eleitor pode conferir as informações antes de confirmar.

---

# 🔢 Teclado numérico

A urna possui um teclado numérico virtual com os números de:

```text
0 1 2 3 4 5 6 7 8 9
