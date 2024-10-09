## Projeto desenvolvido no curso de Laravel Eloquent

Desenvolvido no curso de Laravel Eloquent

### Instalando o projeto

#### Clonar o repositório

```
git clone https://github.com/treinaweb/treinaweb-eloquent-fundamentos-v2.git
```

#### Instalar as depencências

```
composer install
```

Ou em ambiente de desenvolvimento:

```
composer update
```

#### Criar arquivo de configurações de ambiente

Copiar o arquivo de exemplo `.env.example` para `.env` na raiz do projeto
configurar os detalhes da aplicação e conexão com o banco de dados.

#### Criar a estrutura no banco de dados

```
php artisan migrate
```

#### Iniciar o servidor de desenvolvimento

```
php artisan serve
```
