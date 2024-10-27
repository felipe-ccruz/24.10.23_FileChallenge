# Desafio em Java: Manipulação de Arquivos com a Classe File

## Descrição
O objetivo deste desafio é desenvolver um programa que manipule arquivos utilizando a classe `File` do Java. Você deverá criar, ler e modificar arquivos, simulando uma aplicação que realiza o gerenciamento de arquivos de texto. 

### Requisitos:
1. **Criação de Arquivos**:
   - O programa deve criar novos arquivos de texto com base no nome fornecido pelo usuário.
   - Caso o arquivo já exista, o programa deve alertar o usuário e perguntar se deseja sobrescrever o arquivo.

2. **Leitura de Arquivos**:
   - O programa deve ler o conteúdo de um arquivo existente e exibir o texto no console.
   - Se o arquivo não existir, deve ser apresentada uma mensagem de erro ao usuário.

3. **Escrita em Arquivos**:
   - O programa deve permitir que o usuário escreva uma mensagem que será gravada em um arquivo de sua escolha.
   - Caso o arquivo não exista, o programa deve criá-lo antes de gravar o texto.

4. **Listagem de Arquivos**:
   - O programa deve exibir uma lista de todos os arquivos presentes em um diretório específico.

5. **Exclusão de Arquivos**:
   - O programa deve permitir que o usuário exclua um arquivo específico. Antes de excluir, o programa deve confirmar a intenção do usuário.

### Regras:
- Utilize a classe `File` e outras classes associadas como `FileReader`, `FileWriter` e `BufferedReader`.
- O programa deve ser robusto, lidando com exceções como arquivos inexistentes ou problemas de permissões.
- O código deve ser devidamente comentado para que outra pessoa possa entender sua lógica.
  
### Exemplos de Execução:

**Exemplo 1**:  
Usuário tenta criar um arquivo que já existe.
```bash
Digite o nome do arquivo a ser criado: documento.txt
Arquivo já existe. Deseja sobrescrevê-lo? (s/n): n
Operação cancelada.
```

**Exemplo 2**:  
Usuário lê um arquivo existente.
```bash
Digite o nome do arquivo a ser lido: documento.txt
Conteúdo do arquivo:
Este é o conteúdo do arquivo.
```

**Exemplo 3**:  
Usuário escreve em um arquivo.
```bash
Digite o nome do arquivo onde deseja escrever: novo_arquivo.txt
Digite o conteúdo a ser gravado: Esta é uma nova linha de texto.
Arquivo gravado com sucesso.
```

## Considerações Finais:
O desafio deve estimular o uso da classe `File` e o tratamento de exceções adequadas, além de promover boas práticas de desenvolvimento como a verificação da existência de arquivos e o tratamento de erros ao lidar com o sistema de arquivos.