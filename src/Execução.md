Agora que você tem seus arquivos de tradução, pode começar a traduzir os textos em seus arquivos Blade. Em seus arquivos Blade, onde você deseja adicionar texto traduzível, use a função ___()_ ou _trans()_. Por exemplo:

```php
<p>{{ __('Bem-vindo ao meu site!') }}</p>
```

ou

```php
<p> {{ trans('Bem-vindo ao meu site!') }}</p>
```

⚠️ ou ainda, caso exista alguma tag html dentro do texto, é usado __{!! !!}__ para interpretar o conteúdo corretamente. No exemplo abaixo, temos uma tag _strong_, com o conteúdo **site**, então devemos usar __{!! !!}__, do contrário, usa-se apenas __{{ }}__.

```php
<p> {{ trans('Bem-vindo ao meu <strong>site</strong>!') }}</p>
```

⚠️ Para fins de padronização, estamos usando a função **trans** para realização da tradução.

Agora, essas strings podem ser traduzidas para diferentes idiomas em seus arquivos de tradução.

### Exemplos

Considerando o seguite conteúdo dentro de um arquivo:

```php
<li class="active">
    Anunciar Quarto
</li>
```

Se ainda não estiver criado, nesse momento criamos um arquivo _.php_ com o mesmo nome do arquivo _blade_ com o seguinte conteúdo:

```php
return [

];
```

Após isso criamos uma chave que faça sentido dentro do contexto do que estamos traduzindo. Por exemplo, queremos traduzir o texto __Anunciar Quarto__, podemos criar uma chave chamada, por exemplo, de __anunciar_quarto__ com o texto que queremos traduzir, segue abaixo o resultado:

```php
return [
    'anuciar_quarto' => 'Anunciar Quarto'
];
```

⚠️ Notar que todo texto criado deve ser delimitado por aspas simples (**'**).

⚠️ Aspas duplas (**"**) são possívels também, mas por questões de padronização, estaremos usando somente aspas simples ao longo do processo.

Agora que criamos a nossa chave de tradução, podemos realizar a substituição no conteúdo original, observe o resultado abaixo:

```php
<li class="active">
    {{ trans('anuciar_quarto') }}
</li>
```
