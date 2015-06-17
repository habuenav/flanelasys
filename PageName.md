# Pendências Flanelasys #

## Correções ##
  * Verificar segurança de acesso as páginas sem autenticação
  * Verificar layout padrão em todas as telas
  * Sistema ainda permite entrada de veículos mensalista como rotativo
  * Criar relatório de mensalistas
  * Criar ordenação dinâmica na lista de clientes e na lista de veículos estacionados
  * Problemas ao não encerrar o aplicativo e deixa-lo de um dia para o outro, está duplicando o número de cartão
  * Tornar o campo 'cod\_cartao" como único
> `***` Preparar rotina para alterar cadastros com cod\_cartao duplicado
  * Colocar opção de impressão em modo texto ao invés de PDF

## Melhorias ##
  * Exibir lista de RPS gerada a quase 10 dias e que não foram enviadas para a prefeitura.
  * Lista de carros liberados no dia
  * Opção para cadastrar "Crédito/Saldo Devedor" para os rotativos
  * Tornar a coluna des\_placa como unique na tabela fla\_clientes
  * Disponibilizar no "Dashboard" lista de mensalistas com mensalidade "A vencer" e "Vencidos"
  * Permitir alterar/acrescentar dados de clientes durante geração do arquivo de lote
  * RPS
    * No módulo de RPS, ter opção de visualizar recibo PDF da RPS
    * Não ter opção de escolher qual RPS enviar para prefeitura (toda RPS gerada deve ser enviada para a prefeitura)
    * Melhorar a visualização do arquivo de lote
    * Incluir menu de ajuda para envio do lote para o site da prefeitura
  * Implementar módulo lavação
  * Implementar módulo webcam
  * Implementar módulo Matriz e Filiais
  * Opção de login de funcionário há uma ou mais filiais
  * Adaptar tabelas para suporte a multiplos locais
  * Providenciar arquivos de icone.