### Comportamento
- Como admitir erros e aceitar críticas sem levar para o lado pessoal. 
R: Não se pode levar para o lado pessoal, por mais difícil que seja. Assumir uma postura objetiva é possível, descobrir o propósito da bronca e procurar alinhar junto a chefia um plano para corrigir o que foi apontado. 

- Como calçar os sapatos do usuário, e tentar entender sua visão.
R: Coloca-se no lugar do outro com entrega e generosidade,  cognitiva, identificamos o que o outro sente, na empatia emocional, sentimos, de fato, o que o outro está sentindo e na empatia compassiva, queremos ajudar o outro a lidar com sua situação e com suas emoções. 

- Quando pedir ajudar, quando não pedir ajuda.
R: Primeiramente "Eu já tentei resolver o meu problema"?                                                          Após convencer a mim mesma de que preciso de ajuda, devo localizar exatamente o problema e pedir ajuda a outra. 



- Como saber que você está fazendo, naquele momento, a coisa mais importante que deveria estar fazendo.
R: Porque já defini a prioridades: Capturar, Esclarecer, organizar, refletir e engajar.

### Código
- Como ler o código de outras pessoas.
R: Revisar o código de outra pessoa, ajuda a obter algum grau de compreensão do mesmo  é fazer alguma sugestão, revisão do código ajuda gerar resultados concretos.

- Descreva o SOLID com suas proprias palavras. 
R: Apresentar os conceitos principais do conjunto de princípios de boas práticas de programação chamados de SOLID Principles, relacionando-os a padrões de projeto existentes.

Exemplo.:

Public class ClienteController {
      public void save(ClienteVO c)
      {
          if (this.validate(c))
          {
              ClienteDAO.getInstance().save(c);
              this.sendEmail();
          }
      }
      private boolean validate(ClienteVO c) {
          if (c.nome.equals(""))
              return true;
      }
      private void sendEmail()
      {
          MimeMessage msg = new MimeMessage(session);  
          msg.setFrom(new InternetAddress("email@email.com"));  
          ...
          Transport.send(msg);  
      }    
  }
  
O código, tem-se uma fictícia classe ClienteController, onde são criadas algumas funcionalidades relativas a persistência de dados, validação e envio de email.


- Como você sabe que está escrevendo a coisa certa?
R: Apresenta-se o conceito principal do conjunto de boas práticas de programação chamados de SOLID Principles.

- Como você sabe que está escrevendo certo? 
R: Pesquisei sobre o contexto "SOLID" em termos de boas práticas de programação. 


### Pessoal
- Como você estuda/consome informação. Descreva suas fontes, qual é o seu processo e com que frequencia.
R: Estudo atraves de livros, e sites como DEVMIDIA, CODECADEMY e ANDRROID TRAINING.

- Qual é o seu hobby?
R: Leitura, Caminhada e Esportes.
