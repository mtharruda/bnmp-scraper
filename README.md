# bnmp-scraper
Código em Python para automatização e raspagem de informações cadastradas no Banco Nacional de Medidas Penais (BNMP), do Conselho Nacional de Justiça (CNJ).
**Atenção:** é necessário informar chave (código de processo) para a raspagem (ou outra variável, com a necessidade de alteração do código).

## Como usar
Em cada sessão, o sistema solicita ao usuário a verificação via Captcha. Por isso, é preciso realizar a verificação antes de rodar a célula de automatização. 
Durante a análise também foi identificado outro problema: o site funciona por sessões de aproxidamente cinco minutos. Ao término da sessão, o sistema solicita novamente uma verificação. 
Código será atualizado com alternativas para driblar a verificação em captcha. 

