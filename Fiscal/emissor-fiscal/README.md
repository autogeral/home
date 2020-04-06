# emissor-fiscal

Esse projeto será responsável por:
1. Manter "parametrizadas" as tributações federais e estaduais, conforme um analista fiscal cadastre.
2. Ao receber um um "DocumentoFiscal" do "[ERP (DBF)](https://github.com/autogeral/home/blob/master/Fiscal/DBF/README.md)": **calcular os impostos usando as tributações cadastradas**
3. Retornar esse DocumentoFiscal, para [ERP](https://github.com/autogeral/home/blob/master/Fiscal/DBF/README.md), (No presente momento, está apenas retornando um JSON, e o [ERP](https://github.com/autogeral/home/blob/master/Fiscal/DBF/README.md) ainda continua fazendo o processo de: **gerar o xml, assinar, envio para a sefaz, etc**)

O codigo fonte está no seguinte repositorio

1. [emissor-fiscal](https://github.com/cartola-erp/emissor-fiscal)
