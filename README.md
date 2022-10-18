# Gagawin

A to-do list app made in Flutter.

# Arquitetura e tecnologias

O Gagawin é um aplicativo de lista de tarefas feito para Android e IOS com Dart && Flutter. Seu código fonte é aberto para que qualquer pessoa que tenha interesse em contribuir o faça.

As seguintes tecnologias serão utilizadas no desenvolvimento deste projeto:

- A linguagem de programação Dart;
- O framework Flutter;
- O sistema de gerenciamento de banco de dados SQLite.

Inicialmente será utilizada a Arquitetura Hexagonal (caso eu não encontre outra que se adapte melhor ao desenvolvimento de um aplicativo) a fim de tornar o sistema o mais desacoplado possível.

As telas serão desenhadas à mão utilizando o GIMP e/ou o Canvas porque eu não tenho dinheiro para ficar pagando pelos produtos da Adobe.

# Mini-mundo

Os usuários devem poder baixar o aplicativo e cadastrar seus afazeres. Esses afazeres tem título, descrição (opcional), prioridade (muito alta, alta, média, baixa, muito baixa) — por padrão é média —, tags (importante e urgente) — que são opcionais — e status (”A fazer”, “Em progresso” e “Finalizado”). Os afazeres são mostrados na forma de lista dentro do aplicativo e são divididos em “A fazer”, “Em progresso” e “Finalizado”. O usuário deve poder mover as tarefas de um status para outro. Em cada linha que representa uma tarefa deve aparecer uma opção (como um checkbox) que serve para mover uma tarefa para o status “A fazer”. As tarefas finalizadas devem ser mostradas riscadas e com uma coloração acinzentada para se diferenciar das tarefas com outros status.
