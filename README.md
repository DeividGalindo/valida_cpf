<h1 align="center">📝 Projeto Validador de CPF</h1>

## Descrição do projeto

### Objetivo Geral:

Desenvolver um sistema que seja intuitivo e responsivo com a finalidade de verificar se o CPF é válido, proporcionando uma forma de verificar se o CPF é verdadeiro.

### Objetivos Específicos:
- Criar um sistema de fácil uso, permitindo que os usuários consigam verificar se o CPF é verdadeiro.
- Implementar a função de cálculo de CPF que vai verificar a autenticidade do CPF .
- Garantir a compatibilidade do sistema com dispositivos móveis, proporcionando uma experiência fluída e responsiva em smartphones e tablets.

### 🛠 Linguagens de programação

``HTML5``:O projeto utiliza HTML5 para estruturar o conteúdo da aplicação de forma semântica e acessível. A marcação HTML serve como base da interface do sistema, sendo responsável por organizar os elementos visuais e funcionais da página. Neste caso, foi criado um formulário simples que contém um campo de entrada para o usuário digitar seu CPF, um botão para a verificação e uma exibição da mensagem de validação. Toda a estrutura está envolvida pela tag <main>, que destaca a seção principal da aplicação, contribuindo para uma melhor interpretação por navegadores, leitores de tela e mecanismos de busca. Dessa forma, o HTML garante que os elementos estejam corretamente posicionados e compreensíveis, proporcionando uma base sólida para o funcionamento do sistema.

``CSS``: Responsável pela estilização e layout do sistema. Utilizamos o Bootstrap para definir a aparência visual, como cores, fontes, espaçamento e responsividade, garantindo que o sistema tenha um design atraente e adaptável a diferentes tamanhos de tela.  

``Java Script``: A aplicação utiliza JavaScript para realizar a lógica de validação do CPF informado pelo usuário. A função principal validarCPF é responsável por verificar se o CPF é válido. Primeiramente, o código remove quaisquer caracteres que não sejam dígitos e, em seguida, valida a quantidade de números e se todos os dígitos não são iguais.

O algoritmo implementado realiza dois cálculos principais, correspondentes aos dois dígitos verificadores (DV) do CPF. No primeiro cálculo, os nove primeiros dígitos são multiplicados por pesos decrescentes e, após a soma dos resultados, calcula-se o resto da divisão por 11. O mesmo processo é feito com os dez primeiros dígitos para validar o segundo dígito verificador. Caso algum desses valores não coincida com os dígitos informados, a função retorna false.

## 📸 Preview

![preview](imagem/projeto.png)



# Autor

[<img src="Deivid.jpg" width=95><br><sub>Deivid Galindo</sub>](https://github.com/DeividGalindo)