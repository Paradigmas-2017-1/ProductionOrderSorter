funcaoSequencializar tempoFuncional dataInicio horaInicio OPs

Entrada: 
24:00 - 15/04/2017 - 07:00
OPs:
{
	(1, 'PAC', 43, 330, '4120', 2010, 60),
	(1, 'PAC', 49, 330, '4120', 12000, 60),
	(1, 'PAC', 50, 330, '4120', 2010, 60),
	(1, 'PAC', 51, 330, '4120', 12000, 60)
}

(CodEmp, CodOri, NumOrp, CodEtg, CodCre, TmpTpr, TmpFix)

CodEmp - Código da Empresa
CodOri - Código da Origem
NumOrp - Número da Ordem de Produção
CodEtg - Código do Estágio
CodCre - Código do Centro de Recurso
TmpTpr - Tempo Previsto (Minutos)
TmpFix - Tempo Fixo de Set Up (Minutos)


Saída:
{
	(1, 'PAC', 43, 330, '4120', '15/04/2017', '07:00', '16/04/2017', '21:30'),
	(1, 'PAC', 49, 330, '4120', '16/04/2017', '21:30', '25/04/2017', '06:30'),
	(1, 'PAC', 50, 330, '4120', '25/04/2017', '06:30', '26/04/2017', '21:00'),
	(1, 'PAC', 51, 330, '4120', '26/04/2017', '21:00', '06/05/2017', '06:00')
}

(CodEmp, CodOri, NumOrp, CodEtg, CodCre, DataInicial, HoraInicial, DataFinal, HoraFinal)