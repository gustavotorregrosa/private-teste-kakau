Teste Prático de Automação com Selenium

Objetivo: Avaliar a capacidade de usar Selenium para automação de um fluxo RPA.
Cenário

Você deve automatizar um processo que realiza as seguintes tarefas em um site de exemplo:

    Acessar uma página de login e autenticar um usuário.
    Validar que o login foi bem-sucedido por meio de um elemento na página inicial.
    Navegar para uma página de listagem de dados.
    Extrair informações de uma tabela e salvar os dados em um arquivo CSV.

Requisitos

    Implemente os testes usando Python com Selenium.
    Configure o driver para o navegador Chrome.
    Use boas práticas de automação, como:
        Esperas explícitas.
        Organização do código.
    Utilize o módulo unittest para estruturar os testes.

Passos Detalhados

    Autenticação
        Acesse a URL de login: https://example.com/login.
        Utilize as seguintes credenciais:
            Usuário: test_user
            Senha: secure_password.
        Submeta o formulário.

    Validação de Login
        Após o login, valide que o texto Welcome, test_user aparece no elemento com o ID welcome-message.

    Navegação e Extração de Dados
        Navegue até a URL: https://example.com/data-page. (apenas exemplo, você deve utilizar uma url disponível na web ou do gitub)
        Localize uma tabela com o ID data-table.
        Extraia os dados das células da tabela e armazene-os no formato de lista de listas (ou seja, linhas e colunas).

    Salvar os Dados
        Salve os dados extraídos em um arquivo CSV com o nome extracted_data.csv.

Critérios de Avaliação

    Corretude: O script realiza as tarefas descritas corretamente.
    Boas Práticas: O código é organizado, usa esperas explícitas e tem boa legibilidade.
    Uso de unittest: Os testes estão estruturados corretamente no formato de casos de teste.
    Gestão de Erros: O código lida adequadamente com situações inesperadas, como elementos ausentes.


