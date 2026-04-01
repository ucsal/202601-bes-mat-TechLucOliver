Aplicando o primeiro principio SOLID (Princípio da Responsabilidade Única): <p>
Alterado a localidade do método calcularNota da classe App para a classe Tentativa. <p>
Alterado a localidade do método imprimirTabuleiroFen da classe App para uma classe (Xadrez) em um novo package (View). <p>
Alterado a localidade dos atributos estáticos da classe App para outra classe (DataBase).<p>
Alterado a localidade do menu de opções da classe App para uma nova classe (ComandoDeConsole) através do método exibirMenu().<p>
Scanner para input centralizado na classe ComandoDeConsole.<p><p>
***********<p>
Aplicando o segundo princípio do SOLID (Princípio do Aberto/Fechado).<p>
Alterado a classe Questao para abstrata.<p>
Criados métodos exibirAluno() e verificaResposta(String entrada).<p>
Criada a classe QuestaoXadrez estendendo a classe Questao encapsulando a lógica do jogo.<p>
Implementado o exibirAluno() para imprimir o enunciado e mostrar o tabuleiro.<p>
Implementado o verificaResposta(String entrada) contendo a lógica de normalização de chars e comparação com a alternativa correta.<p>
Encapsulados os atributos fenInicial e alternativas<p>
Simplificado o método aplicarProva()<p>