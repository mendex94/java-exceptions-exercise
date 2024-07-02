# Java Exception Exercise

## Introduction

Fazer um programa para ler os dados de uma reserva de hotel (número do quarto, data de check-in e data de check-out) e mostrar os dados da reserva, inclusive sua duração em dias. Em seguida, ler novas datas de check-in e check-out, atualizar a reserva, e mostrar novamente a reserva com os dados atualizados. O programa não deve aceitar dados inválidos para a reserva, conforme as seguintes regras:

- Alterações de reserva só podem ocorrer para datas futuras;
- A data de check-out deve ser maior que a data de check-in.

## Example

```bash
Room number: 8021
Check-in date (dd/MM/yyyy): 23/09/2020

Check-out date (dd/MM/yyyy): 26/09/2020
Reservation: Room 8021, check-in: 23/09/2020, check-out: 26/09/2020, 3 nights

Check-in date (dd/MM/yyyy): 24/09/2020
Check-out date (dd/MM/yyyy): 25/09/2020
Error in reservation: Check-out date must be after check-in date
```