# EXERCICIO30AGOSTO
Exercício da aula de Programação de Computadores - 30/08/2024


// Variáveis
string nome, sobrenome, nomeCompleto, mensagem;

// Entrada
Console.Write("Digite seu nome........: ");
nome = Console.ReadLine()!;

Console.Write("Digite seu sobrenome...: ");
sobrenome = Console.ReadLine()!;

// Processamento
nomeCompleto = $"{nome} {sobrenome}";
mensagem = $"Olá, {nomeCompleto.ToUpper().Replace("A", "@")}!";


// Saída
Console.WriteLine(mensagem);

