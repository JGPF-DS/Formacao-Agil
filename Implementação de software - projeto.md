

Segue a versão do trabalho "fluxo comercial" estarei evoluindo no desenvolvimento, caso tenham interesse em participar, por favor, sinalizem.

Próximos passos: Em Power BI

a)modelagem dos dados O.L.A.P.
c) modelo de BI - Snow Flake
d)definir as tabelas fato: (segmentar ou não)
e) definir os tabelas de dimensão
f)Carregar as tabelas com dados fake
g) validar os indicadores


- SLA é um termo do inglês que significa Service Level Agreement, isto é: **Acordo de Nível de Serviço**. Portanto, pode ser aplicado a qualquer tipo de serviço prestado de uma empresa para a outra.
- OLAP é a capacidade para manipular e analisar um grande volume de dados sob múltiplas perspectivas. As aplicações OLAP são usadas pelos gestores em qualquer nível da organização para lhes permitir análises comparativas que facilitem a sua tomada de decisões diárias.
- O modelo de dados Snowflake é uma estrutura lógica de dados que facilita a análise de dados complexos. Esse nome porque se parece visualmente com um floco de neve, devido ao relacionamento entre os dados. Nesse modelo, várias dimensões (lookups) se relacionam com uma tabela “fato”, de modo que os dados ficam em uma cascata (hierarquia) e mais distantes da tabela “fato”. O dado passa por todos os outros objetos até atingir o destino final: a análise.
	- https://www.mindtek.com.br/2022/11/modelagem-de-dados-snowflake/
- Tabela de fatos ou tabelas de factos é a tabela dominante de um esquema de modelagem tipo estrela, criado pelo Dr. Ralph Kimball, em um modelo multidimensional, e tem como característica principal a presença de dados altamente redundantes para se obter um melhor desempenho.

## Da apresentação
Questões que o software deve responder:
1. KPI
	1. [x]  ```DEFINIR O SLA por area (definicao dos projetos (PMG) e ou valor da proposta.```
		1. [x] ```Medição dos resultados = SLA por atividade x area
		2. [ ] ```Aumentar a taxa de conversao de 10% para 35% (cotacao x ordem de venda)
		3. [ ] ````Monitorar o indicador da faixa de rentabilidade por proposta
			1. [ ] Faixas <0 ate 10% vermelho
			2. [ ] Faixas >10% ate 15% amarelo
			3. [ ] Faixas >15% ate 25% verde
			4. [ ] Faixas >25% roxo```
		4. ```Monitorar canal de venda
			1. [ ] >10% verde
			2. [ ] <10% até 2% amarelo
			3. [ ] <2% vermelho
		5. ```Indicador de qualidade (reclamações)
			1. [ ] 0 verde
			2. [ ] de 1 a 3 amarelo
			3. [ ] de 3 a 8 vermelho
			4. [ ] acima

### Conhecer os motivos das perdas de propostas (elaborar FCA)
Fatos
causas 
Acoes

1. OKR 
	1. O:
		1.  Construir relacionamentos sólidos com nossos clientes;
		2. acelerar o crescimento de vendas e a locação;
		3. Ser referência no mercado de módulo habitacional.
	2. KR: 
		1. Ter 200 novos leads
		2. ampliar a venda no mercado de construção cível em 50% no Q4;
		3. Atingir 20% de market share.

Nós vamos fazer um processo de monitorar a operação.

## Considerações do Mario:
- [ ] Todos os processos são realmente necessários?
- [ ] Todas as caixinhas do fluxo tem um dono?
- [ ] As coisas estão modularizadas?
- [ ] É possível eliminar alguma etapa?
- [ ] Discutir o modelo do Bizagi.
- [ ] O SLA conta quando você definiu alguma coisa.
- [ ] Se você conseguir colocar as coisas em paralelo, ou seja eliminar os processos sequenciais agiliza o processo
- [ ] Inserir marcos contratuais.
- [ ] Conhecer os motivos das perdas das propostas.
	- [ ] Seria melhor inserido em gestão do conhecimento. 
	- [ ] Não faria parte dos processos da empresa
	- [ ] Faria parte de um departamento de marketing intelligence.
	- [ ] Sugestão de um colega, levar para o comercial.
- [ ] Dividir responsáveis por áreas
	- [ ] Incentivos 
	- [ ] processos flexiveis
- [ ] Rodar o processo inicial para entender a capacidade produtiva

---
### Para terminar o Dashboard
- Pr Venda - preço de venda do contrato
- Pr Realizado -valor após a execução ou seja quanto realmente foi gasto.
	Porém na tabela o Pr Realizado, todos os valores estão multiplicados por ==0,95== então as faixas de rentabilidade serão ==sempre as mesmas.==
	Sugerir ao Marcelo para que _sejam alterados_ esses valores.


Vamos Precisar de colunas nas planilhas para auxiliar no Dashboard:
- [ ] Fechado %
- [ ] Ganhos
- [ ] Perdas
