# Erros ao tentar executar um git pull

## Quando as branchs divergirem

Em algum momento as branchs podem divergir isso é causado devido a quandidade de commits em uma forma diferente em outra.
isso pode ser resolvido com um 

´git pull´ 

porém a configuração do git pode esta para rebase o que espera que isso seja feito ao inves de um pull.
A configuração pode ser desativada rodando 

´git config pull.rebase false´

Apos isso pode rodar o git pull origin master ou main


´git pull origin master´

ou 

´git pull origin main´

