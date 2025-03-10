# bnmp-scraper
Código em Python desenvolvido para automatização e raspagem de dados do Banco Nacional de Medidas Penais (BNMP), do Conselho Nacional de Justiça (CNJ). O notebook foi utilizado para a produção da reportagem: **[Mais de 40 pessoas são procuradas pela Justiça há pelos menos dez anos na região de Sorocaba, indicam dados do CNJ]([url](https://g1.globo.com/sp/sorocaba-jundiai/noticia/2024/12/09/mais-de-40-pessoas-sao-procuradas-pela-justica-ha-pelos-menos-dez-anos-na-regiao-de-sorocaba-indicam-dados-do-cnj.ghtml))**

**Atenção:** é necessário informar chave (código de processo) para a raspagem (ou outra variável, com a necessidade de alteração do código).

## Como usar
Em cada sessão, o sistema solicita ao usuário a verificação via Captcha. Por isso, é preciso realizar a verificação antes de rodar a célula de automatização. 
Durante a análise também foi identificado outro problema: o site funciona por sessões de aproxidamente cinco minutos. Ao término da sessão, o sistema solicita novamente uma verificação. 
Código será atualizado com alternativas para driblar a verificação em captcha. 

