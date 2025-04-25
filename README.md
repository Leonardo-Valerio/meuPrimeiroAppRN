# Projeto de Aplicativo para Controle de Consultas Médicas

## Leonardo Moreira Valério — RM550988

Este projeto é um aplicativo mobile desenvolvido com o objetivo de facilitar a organização de consultas médicas. Ele permite que o usuário visualize, edite e salve informações de forma prática, mantendo todos os dados armazenados localmente no dispositivo.

---

## Funcionalidades do Aplicativo

- **Lista de Consultas**  
  O aplicativo exibe uma lista com todas as consultas cadastradas, permitindo ao usuário ter uma visão geral dos compromissos médicos.

- **Cadastro e Edição de Consultas**  
  É possível inserir novas consultas e também editar informações de consultas já existentes, diretamente pela interface do app.

- **Salvamento Local com AsyncStorage**  
  Os dados são armazenados utilizando o recurso de AsyncStorage, o que garante que as informações fiquem salvas mesmo que o aplicativo seja fechado.

---

## Tecnologias Utilizadas

- React Native
- AsyncStorage

---

## Instruções para Executar o Projeto

### Requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn
- Expo CLI instalado (caso utilize o Expo)

### Passos para instalação

1. Clone o repositório:

```
git clone https://github.com/Leonardo-Valerio/meuPrimeiroAppRN
```

2. Acesse o diretório do projeto:

```
cd meuPrimeiroAppRN
```

3. Instale as dependências:

```
npm install
```
ou

```
yarn install
```

4. Inicie o servidor de desenvolvimento:

```
npm start
```
ou

```
yarn start
```

5. Utilize o Expo Go em seu dispositivo físico ou emulador para abrir o aplicativo.

---

## Informações Adicionais

Na tela inicial, o usuário pode visualizar todas as consultas já registradas. Novas consultas podem ser adicionadas preenchendo informações como data, horário e nome do médico. Também é possível editar ou excluir qualquer item da lista. Todos os dados são mantidos no armazenamento local do dispositivo com o uso do AsyncStorage, garantindo persistência mesmo após o fechamento do app.
