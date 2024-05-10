# <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"> Orientação a Objetos na Prática com Java
www.dio.me


#### Desenvolvido na linguagem Java por:
- [Marcos Shirafuchi](https://github.com/marcosfshirafuchi)
# Desafio 02 / 05 - Registro de Transações Bancárias com Stream API
## Descrição
Você está aprimorando o programa anterior e agora deseja utilizar a Stream API do Java para processar as transações bancárias de forma mais eficiente.
## Entrada


* O programa solicitará ao usuário que informe o saldo inicial da conta.
* Em seguida, o programa solicitará a quantidade total de transações que o cliente deseja realizar.

### Entrada de Transações:
* Para cada transação, o programa solicitará ao usuário:
  * O tipo de transação: Digite 'D' para depósito ou 'S' para saque.
  * O valor da transação.
## Saída

* Utilizando a Stream API, o programa armazenará cada transação, que incluirá um tipo (Depósito ou Saque) e um valor.
* Ao final das transações, o programa exibirá o saldo final da conta e a lista de transações.


## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
<table>
  <thead>
    <tr align="left">
      <th>Entrada</th>
      <th>Saída</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>100<br>
           2<br>
           d<br>
         10<br>
          s<br>
         20<br>
      </td>
      <td>Saldo: 90.0<br>
Transacoes:<br>
d de 10.0<br>
s de 20.0<br>
      </td>
    </tr>
    <tr>
      <td>5000<br>
1<br>
d<br>
500<br>
      </td>
      <td>Saldo: 5500.0<br>
Transacoes:<br>
d de 500.0<br></td>
    </tr>
    
  </tbody>
  <tfoot></tfoot>
</table>





