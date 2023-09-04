# Exercicios de estrutura sequencial feito em python
<br>
<b>1 - Faça um Programa que mostre a mensagem "Alo mundo" na tela:</b><br>
	print("Ola mundo")<br><br>

<b>2- Faça um Programa que peça um número e então mostre a mensagem O número informado foi [número].</b><br>
	numero = int(input("Digite um numero: "))<br>
	print("O número informado foi: " + str(numero))<br>

<b>3- Faça um Programa que peça dois números e imprima a soma.<br></b>
	numero = int(input("Digite o primero numero: "))<br>
	numero2 = int(input("Digite o segundo numero: "))<br>
	soma = int(numero) + int(numero2)<br>
	print("soma dos numeros: " + str(soma))<br>

<b>4- Faça um Programa que peça as 4 notas bimestrais e mostre a média.<br></b>
	numero = int(input("Digite a primeira nota: "))<br>
	numero2 = int(input("Digite a segunda nota : "))<br>
	numero3 = int(input("Digite a terceira nota: "))<br>
	numero4 = int(input("Digite a quarta nota: "))<br>
	media = ((int(numero) + int(numero2) + int(numero3) + int(numero4)) / 4)<br>
	print("A media das notas: " + str(media))<br>

<b>5 - Faça um Programa que converta metros para centímetros.<br></b>
	metros = int(input("Digite a distancia em metros: "))<br>
	conversao_centimetros = int(metros * 100)<br>
	print("A distancia em centimetros: " + str(conversao_centimetros))<br>

<b>6- Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.<br></b>
	raio_circulo = float(input("Digite o raio do circulo: "))<br>
	area = float(3.14 * (raio_circulo * raio_circulo))<br>
	print("A area do circulo: " + str(area))<br>

<b>7- Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.<br></b>
	raio_circulo = float(input("Digite o raio do circulo: "))<br>
	area = float(3.14 * (raio_circulo * raio_circulo))<br>
	area2 = (float(area) * 2)<br>
	print("A area do circulo: " + str(area2))<br>

<b>8- Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.<br></b>
	dinheiro_horas = float(input("Ganhos por horas: "))<br>
	horas_trabalhadas = int(input("Horas trabalhadas: "))<br>
	soma = (float(dinheiro_horas) * int(horas_trabalhadas))<br>
	print("Salario do mês:" + str(soma))<br>

<b>9 - Faça um Programa que peça a temperatura em graus Fahrenheit, transforme e mostre a temperatura em graus Celsius.<br></b>
C = 5 * ((F-32) / 9).
	temperatura_fehr = float(input("Temperatura em fahrenheit: "))<br>
	conversao_celsius = float(5 * ((temperatura_fehr-32) / 9))<br>
	print("Conversão em Celsius: " + str(conversao_celsius))<br>

<b>10 - Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Fahrenheit.<br></b>
	temperatura_celsius = float(input("Temperatura em Celsius: "))<br>
	conversao_fehr = float((temperatura_celsius * 9 / 5) + 32)<br>
	print("Conversão em fahrenheit: " + str(conversao_fehr))<br>

<b>11 - Tendo como dados de entrada a altura de uma pessoa, construa um algoritmo que calcule seu peso ideal, usando a seguinte fórmula: (72.7*altura) - 58<br></b>
	altura = float(input("Digite a altura: "))<br>
	peso_ideal = float((72.7*altura) - 58)<br>
	print("Peso ideal: " + str(peso_ideal))<br>

<b>12 - Tendo como dado de entrada a altura (h) de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas:<br></b>
	altura = float(input("Digite a altura: "))<br>
	sexo = int(input("1 - Masculino / 2 - Feminino: "))<br>
	peso_ideal = float((72.7*altura) - 58 if sexo == 1 else (62.1*altura) - 44.7)<br>
	print("Peso ideal: " + str(peso_ideal))<br>
