Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
let dia da semana = sábado, domingo;
let chute = prompt('qual é o dia da semana?');
if (chute == dia da semana) {
    alert('Bom fim de semana!');
} else { 
    alert ('Boa semana!');
}

Correção do exercício 1:
diaDaSemana = prompt('Qual é o dia da semana?');
if (diaDaSemana == 'Sábado') {
    alert('Bom fim de semana!');
} else if (diaDaSemana == 'Domingo') {
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}

Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
numero = prompt('Digite um número');
if (numero > 0) {
    alert('Número positivo!');
} else { alert('Número negativo!');
}

Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
pontuação = 101
if (pontuação >= 100) {
    alert('Parabéns, você venceu!);
} else { alert('Tente novamente para ganhar.);
}
Correção dp exercício 3
pontuacao = 105;
if (pontuacao > 100) {
    console.log('Parabéns, você venceu!');
} else {
    console.log('Tente novamente para ganhar.');
}
Aqui eu não me atentei ao pedido de a mensagem aparecer no console. 

Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
let saldoDaConta = 100
alert (`O saldo da conta é R$${saldoDaConta}`);

Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
let nome = prompt ('Qual o seu nome?');
alert(`Bem-vindo $nome`);