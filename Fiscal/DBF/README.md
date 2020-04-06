# DBF
A parte do DBF neste projeto será: responsável pelo o envio de um "DocumentoFiscal", para a API ([emissor-fiscal](https://github.com/autogeral/home/tree/master/Fiscal/emissor-fiscal)).
Os pacotes referente as classes de integração são os seguintes, no **projeto DBFModel**:

![Pacotes de integração](https://github.com/autogeral/home/blob/master/Fiscal/imgs/01%20-%20Pacotes%20Das%20Classes%20de%20Integracao.png?raw=true)

O projeto referente a NFE(geração de xml etc) está no **projeto "NfeIntegracao4"**, as classes mexidas, para fazer com que envie o DocumentoFiscal, para a [API](https://github.com/autogeral/home/tree/master/Fiscal/emissor-fiscal), foram:

```
IntegracaoNfe
IntegracaoNfeEmissorFiscal
```

O codigo fonte está dividido nestes três repositorios do subversion

1. [code](http://svn.autogeral.com.br/code)
2. [sped](http://svn.autogeral.com.br/sped)
3. [repositorio](http://svn.autogeral.com.br/repositorio)
