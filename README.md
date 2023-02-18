# Tradução do Laravel para Português do Brasil

## Instalação

1.  Instale o pacote

```shell
composer require danpalmieri/laravel-brazilian-portuguese --dev
```

2.  Publique as traduções

```shell
php artisan vendor:publish --tag=laravel-brazilian-portuguese
```

3.  Configure o Framework para utilizar 'pt_BR' como linguagem padrão

```
// Altere o arquivo config/app.php para:
'locale' => 'pt_BR',
```

4. Configure o framework para utilizar 'America/Sao_Paulo' como zona padrão

```
// Altere o arquivo config/app.php para:
'timezone' => 'America/Sao_Paulo',
```

## Versões do Laravel suportadas

-   10.x
-   9.x
-   8.x
