# Validador de PIT
Conjunto de macros em excel para auxiliar na elaboração do PIT do IFS que devem ser importados para o SIGAA.

- Atualmente trabalha com carga horária diária de 8 horas.


![Exemplo de uso](ExemploDeUso.gif?raw=true)


# Uso 

Para fazer uso siga o seguinte roteiro:

1. Realize o [download da planilha](modelo-pit-2019.1.Macro.xlsm?raw=true);
1. Abra a planilha e habilite a opção de macros;
1. Edite o conteúdo da `Planilha 1`

   - As células devem ser preenchidas com texto;
   - O cálculo é realizado por dia;
   - O validador contará as células que foram mescladas que contém texto.
   
1. Vá para a planilha resumo e efetue dois cliques em cada uma das celulas que você quer que seja contabilzada.
1. Quando concluir o ajuste de horário, selecione o conteúdo da `Planilha 1`, copie e cole no arquivo disponibilizado pelo Sigaa (menu PIT).

# Problemas conhecidos

- Atualização automática da tabela resumo

Para evitar o alto processamento e travamentos de edição enquanto o cálculo era realizado automaticamente, este foi desabilitado e para contornar é necessária a atualização manual das células.

# Como contribuir

- Registre sua ocorrência neste repositório através do [link ISSUES](https://github.com/CBSIIFSLagarto/ValidadorPIT/issues).
