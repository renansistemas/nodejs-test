# Projeto NODEJS-TEST

## Descrição
NODEJS-TEST é um projeto simples em Node.js que implementa operações matemáticas básicas (soma, subtração, multiplicação e divisão) utilizando módulos.

## Tecnologias Utilizadas
- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **JavaScript**: Linguagem de programação utilizada.
- **Módulos Node.js**: Para modularização e reutilização de código.

## Estrutura do Projeto
```
NODEJS-TEST/
├── calc.js        # Arquivo principal que chama os módulos matemáticos
├── somar.js       # Módulo para soma
├── sub.js         # Módulo para subtração
├── multi.js       # Módulo para multiplicação
├── div.js         # Módulo para divisão
├── package.json   # Arquivo de dependências do Node.js (se aplicável)
└── README.md      # Documentação do projeto
```

## Como Rodar o Projeto
### 1. Instalar o Node.js
Certifique-se de que o Node.js está instalado em sua máquina. Caso não esteja, faça o download e instale a partir do site oficial: [Node.js](https://nodejs.org/)

### 2. Clonar o Repositório
```sh
git clone <URL_DO_REPOSITORIO>
cd NODEJS-TEST
```

### 3. Executar o Projeto
```sh
node calc.js
```

Ao executar esse comando, o terminal exibirá os resultados das operações matemáticas definidas no arquivo `calc.js`.

## Como Usar o Projeto
O arquivo `calc.js` importa os módulos de operações matemáticas e executa os cálculos com valores fixos. Caso queira modificar os valores de entrada, altere os argumentos passados para as funções dentro de `calc.js`:

Exemplo de edição:
```js
console.log(somaFunc(50, 30));  // Resultado esperado: 80
console.log(subFunc(100, 20));  // Resultado esperado: 80
console.log(multiFunc(5, 5));   // Resultado esperado: 25
console.log(divFunc(40, 8));    // Resultado esperado: 5
```

## Possíveis Melhorias
- Criar uma interface web ou CLI interativa para entrada de números.
- Adicionar testes automatizados para validar os cálculos.
- Implementar tratamento de erros para divisão por zero.
- Converter para `ES6 Modules` e usar `import/export` ao invés de `require/module.exports`.

## utor
Renan Sistemas