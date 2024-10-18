publicado hein: https://sorteador-grunt-opal-six.vercel.app/

 # Projeto Sorteador de Números

Este é um projeto simples de um sorteador de números desenvolvido como parte de um exercício prático. O objetivo do projeto é criar uma página web que permite ao usuário definir um número máximo e, em seguida, sortear um número aleatório dentro desse intervalo.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Grunt (para automação de tarefas)

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

```
sorteador/
├── css/
│   └── styles.css  # Arquivo CSS para estilização
├── js/
│   └── script.js  # Arquivo JavaScript para funcionalidades
├── index.html  # Página principal do projeto
├── Gruntfile.js  # Configurações do Grunt
├── package.json  # Gerenciamento de dependências e scripts
└── README.md  # Documentação do projeto
```

## Instalação

Para executar o projeto, siga os passos abaixo:

1. **Clonar o Repositório:**
   ```sh
   git clone https://github.com/rodrigobergenthal/Sorteador_Grunt.git
   cd sorteador
   ```

2. **Instalar Dependências:**
   Certifique-se de ter Node.js e npm instalados no seu sistema. Em seguida, instale as dependências do projeto:
   ```sh
   npm install
   ```

3. **Executar o Projeto:**
   Use o Grunt para iniciar um servidor local e visualizar a aplicação em seu navegador:
   ```sh
   grunt serve
   ```

## Uso

1. **Navegue até a Aplicação:**
   Abra o navegador e acesse `http://localhost:8000` para ver a aplicação em execução.

2. **Defina um Número Máximo:**
   No campo "Número Máximo", insira o valor máximo desejado para o sorteio (mínimo 2).

3. **Sortear um Número:**
   Clique no botão "Sortear Número" para obter um número aleatório dentro do intervalo definido. O resultado será exibido abaixo do formulário.

## Personalização

- **Estilos CSS:**
  Todas as estilizações estão contidas no arquivo `css/styles.css`. Você pode modificar os estilos conforme necessário para ajustar a aparência da aplicação.

- **JavaScript:**
  O arquivo `js/script.js` contém o código JavaScript responsável pela lógica de geração do número aleatório. Você pode editar este arquivo para adicionar mais funcionalidades ou ajustar a lógica atual.

## Autor

- [Rodrigo Bergenthal](https://github.com/rodrigobergenthal)

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Espero que este README forneça uma visão clara e detalhada do seu projeto. Se precisar de mais informações ou ajustes, sinta-se à vontade para perguntar! ✨
