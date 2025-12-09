# Live News -- Web Scraping em Tempo Real

O **Live News** é um projeto em Python que realiza web scraping contínuo
de portais de notícias brasileiros e exibe as atualizações diretamente
no terminal.

## Como Usar

Antes de visualizar as últimas notícias, é importante configurar os
sites ativos.

### ⚠️ **Primeiro Passo Obrigatório**

Ao iniciar o programa, vá até a **opção 2 (Adicionar Site)** para
escolher os portais de notícias que deseja acompanhar.\
Por padrão, **nenhum site está ativado**, então é necessário selecionar
pelo menos um.

Após adicionar os sites desejados, pressione **0** para voltar ao menu e
então selecione a **opção 1 (Últimas Notícias)** para visualizar as
atualizações coletadas.

Se quiser remover algum site posteriormente, basta ir à **opção 3
(Remover Sites)**.

## Funcionalidades

-   Atualização automática das notícias
-   Paginação no terminal
-   Abertura das matérias no navegador
-   Adicionar/remover sites ativos
-   Thread dedicada para scraping em segundo plano

## Execução

``` bash
python live_news.py
```

## Estrutura

    live_news.py
    scraping_sites/
        site.py

## Comandos
| Comando | Função |
|--------|--------|
| **P** | Próxima página |
| **A** | Página anterior |
| **L** | Abrir matéria |
| **V** | Voltar |


#
