# API de tratamento de dados:

Uma API que recebe informações da API do Github e faz o tratamento dos dados para enviar para a aplicação;
Todas as funções estão cobertas por testes com Jest.js com cobertura gerada pelo Instambul;

## Endpoints:

Dados base do perfil
{
    Apelido,
    Imagem de perfil,
    Nome,
    Link do perfil
}

- `http://localhost:{PORT}/{USER}/base`

Dados de todos os repositórios publicos que estão no seu perfil
{
    id,
    titulo do repositório,
    link do repositório,
    linguagem principal
} 

- `http://localhost:{PORT}/{USER}/repos`

Compilado de todas as linhas de codigo de cada linguagem usada nos repositórios publicos
{
    linhas de código
}

- `http://localhost:{PORT}/{USER}/lang`

Compilado de datas dos últimos eventos do github
{
    datas: quantidade de eventos
}

- `http://localhost:{PORT}/{USER}/events`
 
## Atualizações 🎉:

- Criar endpoint da API do ChatGPT em adições futuras da aplicação;
- Criar endpoint de conexão com banco de dados;
