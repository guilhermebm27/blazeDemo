### Executando o JMeter | GUI (Interface Gráfica)
1. Mude para o bin diretório
2. Execute o arquivo jmeter ou jmeter.bat (Windows).

<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/341ed141-765d-4db0-9a18-cdfcb86d9d3b" width="1000" />
</p> 

Gráfico demonstrando o Ramp Up:

<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/4a18b803-8e7c-48de-ac67-5353429e1a22" width="1000" />
</p> 

Este gráfico é o resultado da rampagem baseado nos parâmetros informados. Ele foi adicionando as threads (TC) gradativamente até atingir os 1 segundo (RU) e, partir deste ponto, ele seguiu executando requisições simultaneamente e continuamente durante 1 segundos (HT). A duração total dos testes é a soma de RU + HT, que neste caso foi 1 + 1 = 2 segundos. Em resumo, o teste ocorreu conforme esperado.

### Análise dos resultados | GUI (Interface Gráfica)

<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/a708170f-8e5d-4e55-93f1-08f5c5dc4a78" width="1000" />
</p>

O gráfico acima exibe os tempos de resposta (não há nenhum cálculo ou mediana aqui)

### Análise dos resultados tempo de resposta 90th percentil| GUI (Interface Gráfica)

<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/b794befd-a144-41cd-b886-5722ba1fa000" width="1000" />
</p>

Por fim, o relatório de resumo nos traz informações do percentual de erros:

<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/6b352471-499a-446c-a63e-a169cbb17d85" width="1000" />
</p>

 ### Executando o JMeter | Não-GUI/CLI (Linha de Comando)
Executando teste no JMeter no modo Não-GUI, obtemos um consumo menor de memória do processo, com isso, permitindo maior escalabilidade de Threads no teste.

Para executar o JMeter via linha de comando:
Exemplo:
<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/111b0bb8-fa73-4ad6-9461-39152875dc2e" width="500" />
</p> 

### Análise dos resultados | Não-GUI/CLI (Linha de Comando)
<p float="left">
 <img src="https://github.com/guilhermebm27/blazeDemo/assets/31962792/68be9762-7081-4dd7-8b6c-ad3729cb0fc5" width="1000" />
</p>

---------------------------------------------------------------------

### blazeDemo

Desenvolva um script de performance para o seguinte cenário:
URL: https://www.blazedemo.com

Cenário: 
* Compra de passagem aérea - Passagem comprada com sucesso.

Critério de Aceitação:
* 250 requisições por segundo com um tempo de resposta 90th percentil inferior a 2 segundos.

Instruções
* Escolha entre JMeter e Gatling
* Monte um teste de carga e um teste de pico que satisfaçam a vazão do critério de aceitação.
* Anexe o relatório da execução, e explique se o critério de aceitação foi satisfatório ou não, além dos motivos que te levaram a essa conclusão.
* Crie o repositório no GitHub (público) e COPIE E COLE o link aqui. Desenvolva a automação e suba o código no repositório (dica: crie primeiro o repositório, copie o link, cole neste campo e submeta o formulário).
* Não se esqueça do README.md, que deve conter
   - Instruções para a execução do script
   - Relatório de execução dos testes
   - Demais considerações pertinentes ao teste
 


 
