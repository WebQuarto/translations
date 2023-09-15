### Passo 1: Preparação do ambiente

Certifique-se de que você tenha um projeto Laravel em execução. Se ainda não tiver, você pode criar um projeto usando o Composer com o comando:


```bash
composer create-project --prefer-dist laravel/laravel nome-do-projeto
```

Depois de ter seu projeto Laravel instalado e funcionando, siga os próximos passos:

### Passo 2: Configuração da tradução

No Laravel, a tradução é gerenciada usando o serviço de tradução integrado. Primeiro, você precisa configurar as configurações de localização no arquivo config/app.php. Verifique se a configuração locale está definida como o idioma padrão do seu aplicativo (por exemplo, 'en' para inglês). Você também pode adicionar outros idiomas que deseja suportar.

### Passo 3: Criação de arquivos de tradução

Agora, crie arquivos de tradução para cada idioma que você deseja suportar. Você pode usar o comando Artisan para criar automaticamente esses arquivos:


```bash
php artisan make:lang nome-do-idioma
```

Isso criará um arquivo de tradução em _resources/lang/nome-do-idioma/messages.php_. Abra esse arquivo e você verá um array associativo vazio onde você pode adicionar as traduções.

⚠️ Não é necessário executar o comando informado, é possível criar o arquivo manualmente dentro do editor de texto

⚠️ No momento, o interesse é apenas a transferência dos textos em português para o arquivo de idiomas, não sendo necessário adicionar para os demais idiomas. Ou seja, estaremos criando os arquivos dentro de **resources/lang/pt-br**

⚠️ Os arquivos da camada de visão (views) em uma aplicação Laravel possuem a terminação **.blade.php**. Dessa forma, o arquivo de idiomas terá o mesmo nome, removendo-se o sufixo *blade*.

⚠️ Os arquivos de idioma obedecem a mesma estrutura de pastas dos arquivos do projeto, ou seja, o arquivo *resources/views/main/home.blade.php* estará presente em *resources/lang/pt-br/main/home.php*. Observe que o diretório se manteve **main/home.blade.php** para **main/home.php**

### Passo 4: Adição de traduções aos arquivos Blade

Acesse abaixo a documentação de referência para realizar a tradução dos arquivos:

[Adição de traduções no projeto](/Tradução/VisualStudioCode.md)

### Passo 5: Tradução de strings nos arquivos de idioma

Abra o arquivo de tradução correspondente ao idioma que você deseja traduzir em resources/lang/nome-do-idioma/messages.php. Adicione uma entrada associativa para cada string que você deseja traduzir. Por exemplo:


```php
// resources/lang/nome-do-idioma/messages.php
return [
    'Bem-vindo ao meu site!' => 'Welcome to my website!',
];
```

Certifique-se de que as chaves (as frases em português) correspondam às que você usou em seus arquivos Blade.

### Passo 6: Alteração do idioma da aplicação

Para testar a tradução, você pode temporariamente alterar o idioma da aplicação no controlador ou em algum lugar apropriado:

```php
app()->setLocale('nome-do-idioma');
```

Isso fará com que o Laravel use as traduções do idioma especificado.

### Passo 7: Verificação da tradução

Agora, quando você carregar a página, verá os textos traduzidos em vez dos originais, com base no idioma configurado.

Lembre-se de repetir o Passo 5 para cada idioma que deseja suportar. Uma vez que todas as traduções estejam no lugar, você pode alternar o idioma da aplicação com base nas preferências do usuário ou em qualquer lógica apropriada.

Com esses passos, você deve ser capaz de realizar a tradução de arquivos Blade em seu projeto Laravel, tornando seu aplicativo mais acessível a uma variedade de idiomas.
