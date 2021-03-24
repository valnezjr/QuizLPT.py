# QuizLPT.py

print('Vamos começar o quiz interativo!\n')
print('Responda as perguntas com a alternativa indicada à esquerda da resposta!\n')

#Primeira questão
print('Q1:\n'
      'Hoje em dia, o que significa ler com competência?\n'
      '\n(1) - Não ficar apenas no que dizem os textos,mas incorporar o que eles \n' 
      '      trazem para transformar nosso próprio conhecimento.\n'
      '\n(2) - Se apegar ao sentido literal de cada parte do texto,\n'
      '      mantendo sempre o foco no que está explícito.\n'
      '\n(3) - Ler de forma eloquente e rebuscada, mesmo que se trate de uma \n'
      '      leitura introspectiva.\n')

r1 = float(input('Escreva sua resposta conforme instruído: '))

if r1 == 1:
  x1 = 1
  print('Resposta correta, vamos prosseguir!\n')
else:
  print('Resposta errada... vamos para a próxima!\n')
  x1 = 0
#Segunda questão
print('Q2:\n'
      'Qual das alternativas compreende a um conjunto de boas práticas na leitura?\n'
      '\n(1) - Ler apenas quando necessário;\n'
      '      Focar sempre no mesmo tipo de conteúdo;\n'
      '      Colocar a leitura em segundo plano;\n'
      '      Ler por obrigação.\n'
      '\n(2) - Prender-se à um horário fixo;\n'
      '      Restringir sua leitura apenas à redes sociais e bate-papos;\n'
      '      Ler apenas para ajudar a dormir, pois é tedioso.\n'
      '\n(3) - Variar os temas da sua leitura;\n'
      '      Ler durante seus horários de maior foco;\n'
      '      Aplicar a leitura em seus momentos de ociosidade;\n'
      '      Não tomar a leitura como obrigação.\n')

r2 = float(input('Escreva sua resposta conforme instruído: '))

if r2 == 3:
  x1 = x1 +1
  print('Resposta correta, vamos prosseguir!\n')
else:
  print('Resposta errada... vamos para a próxima!\n')

#Terceira questão
print('Q3:\n'
      'Como desenvolver o interesse pela leitura?\n'
      '\n(1) -  É um processo constante e que exige dedicação.\n'
      '       Conforme se lê, começando aos poucos e buscando\n'
      '       temas de seu interesse, a leitura passa a ser\n'
      '       um hábito natural e orgânico.\n'
      '\n(2) -  Começando com uma leitura difícil e inacessível.\n'
      '       Quando se aprende a dirigir um fusca, consegue\n'
      '       dirigir qualquer coisa.\n'
      '\n(3) -  Não lendo nada e esperando que o interesse surja espontaneamente.\n')

r3 = float(input('Escreva sua resposta conforme instruído: '))

if r3 == 1:
  x1 = x1 + 1
  print('Resposta correta, vamos prosseguir!\n')
else:
  print('Resposta errada... vamos para a próxima!\n')

#Quarta questão
print('Q4:\n'
      'Qual das alternativas abaixo compreende a um conjunto de práticas que melhoram o foco na leitura?\n'
      '\n(1) - Ler em locais movimentados;\n'
      '      Ler enquanto se usa o WhatsApp;\n'
      '      Ler em locais barulhentos.\n'
      '\n(2) - Reservar o momento de leitura APENAS para leitura;\n'
      '      Ler apenas enquanto ainda estiver conseguindo absorver\n'
      '      o conteúdo;\n'
      '      Se beneficiar de locais confortáveis e bem iluminados;\n'
      '      Torne a leitura um hábito.\n'
      '\n(3) - Nenhuma das alternativas anteriores.\n')

r4 = float(input('Escreva sua resposta conforme instruído: '))

if r4 == 2:
  x1 =x1 + 1
  print('Resposta correta, vamos prosseguir!\n')
else:
  print('Resposta errada... vamos para a próxima!\n')

#Quinta questão
print('Q5:\n'
      'Qual das alternativas compreede a um conjunto de fatores que irão ajudar' 
      ' a reservar um tempo para a leitura?\n'
      '\n(1) -   Trocar um hábito pela leitura;\n'
      '        Ter sempre um livro na mochila ou bolsa;\n'
      '        Incluir a leitura na rotina de lazer;\n'
      '        Encontrar o tipo ideal de livro para os seus gostos.\n'
      '\n(2) -   Procrastinar;\n '
      '       Aproveitar todos os seus espaços de tempo livre nas redes sociais;\n'
      '        Dar sempre preferência para outras formas de entretenimento.\n'
      '\n(3) - Nenhuma das alternativas anteriores.\n')

r5 = float(input('Escreva sua resposta conforme instruído: '))

if r5 == 1:
  x1 = x1 +1
  print('Resposta correta, vamos prosseguir!\n')
else:
  print('Resposta errada... vamos para a próxima!\n')

print('Você acertou um total de {} questões.'.format(x1))

if x1 ==3:
  print('Você tem certa noção do que ajuda na prática da leitura!\n'\
  'Que tal aplicar essas práticas na leitura de algum desses livros abaixo?\n'\
  '- Harry Potter;\n'\
  '- Percy Jackson;\n'\
  '- The Witcher.\n')
elif x1 >= 4:
  print('Você compreende bem como ter foco na leitura e como aplicar as nossas\n'\
  'dicas. Que tal aplicar essas práticas na leitura de algum desses livros abaixo?\n'\
  '- Memórias Póstumas de Brás Cubas;\n'\
  '- 1984;\n'\
  '- O Iluminado.\n')
else:
  print('Aparetemente, você não tem tanta familiaridade com a leitura. Que tal mudar\n'\
    'isso e começar pelo básico? Leia algum dos livros abaixo:\n'\
    '-O Pequeno Príncipe;\n'\
    '-Reinações de Narizinho;\n'
    '-As Aventuras de Alice no País das Maravilhas.')
