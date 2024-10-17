Horário Escolar - Sistema de Organização de Horários para Professores
Descrição do Projeto
Este projeto tem como objetivo o desenvolvimento de um Software de Organização de Horários voltado para instituições de ensino. Ele visa ajudar na gestão e distribuição de aulas de professores de forma eficiente e sem conflitos, assegurando que as turmas e os professores tenham seus horários organizados de maneira clara e acessível. Com um sistema flexível, o software permite ajustes manuais, validação de conflitos e exportação de horários em PDF.

Funcionalidades
Cadastro de Professores: Permite adicionar novos professores, definindo o número de aulas por dia e por semana.

Cadastro de Turmas: Funcionalidade para registrar turmas, associando ano e série.

Cadastro de Disciplinas: Possibilita cadastrar disciplinas e vinculá-las a professores e turmas.

Gestão de Horários: Atribuição automática de horários, respeitando regras para evitar conflitos entre turmas e professores.

Visualização de Horários: Exibição do horário semanal, permitindo filtragens por professor, turma e disciplina.

Validação de Conflitos: O sistema detecta e impede conflitos de horários, como aulas simultâneas para o mesmo professor ou turma.

Flexibilidade: Funcionalidade que permite ajustes manuais no horário, priorizando os registros manuais e ajustando os horários automaticamente para evitar sobreposições.

Exportação em PDF: Gera o horário semanal em formato PDF, salvo automaticamente na pasta de Downloads, com incremento automático de nome de arquivos para evitar substituições.

Registro Manual de Horários: O usuário pode adicionar horários manualmente e estes terão prioridade sobre os horários gerados automaticamente.

Pré-Requisitos
Python 3.x
Bibliotecas Necessárias:
tkinter (para a interface gráfica)
reportlab (para geração de PDFs)
os (para manipulação de arquivos e caminhos)
datetime (para manipulação de datas e horários)
Como Usar
1. Clonando o Repositório
git clone https://github.com/seuusuario/horario-escolar.git
cd horario-escolar

2. Instalando as Dependências
Certifique-se de que você tenha o Python 3.x instalado. Em seguida, instale as bibliotecas necessárias com o comando:
pip install reportlab

3. Executando o Programa
Basta executar o arquivo principal para iniciar a aplicação:
python main.py
4. Funcionalidades Passo a Passo
Adicionar Curso: Inicie o processo registrando os cursos disponíveis.
Adicionar Disciplina: Após adicionar os cursos, registre as disciplinas e vincule-as a professores e turmas.
Adicionar Professores: Insira o nome do professor e defina a quantidade de aulas por semana. O sistema perguntará se deseja adicionar mais professores.
Organizar Horários: O sistema distribuirá as aulas automaticamente sem conflitos.
Visualizar Horários: Use o botão de visualização para ver os horários por professor, disciplina e turma.
Salvar PDF: Exporte o horário gerado para um arquivo PDF, salvo automaticamente na pasta Downloads.
Horário Manual: Se necessário, adicione horários manualmente e o sistema ajustará automaticamente os demais horários para evitar sobreposições.
Estrutura do Projeto

├── README.md               # Instruções do projeto
├── main.py                 # Arquivo principal do sistema
├── gui.py                  # Interface gráfica (Tkinter)
├── schedule_manager.py      # Lógica de distribuição de horários
└── exports/                # PDF gerados (salvos automaticamente)
Exemplos de Uso
Cadastro de Professores
No cadastro de professores, insira o nome e o número de aulas por semana. Após adicionar um professor, será perguntado se deseja adicionar mais. Se não, você pode seguir para a próxima etapa.

Visualização de Horários
Após organizar os horários, utilize a funcionalidade de Visualização de Horários para verificar a distribuição semanal de cada turma e professor.

Exportação em PDF
Clique no botão de exportação para gerar o arquivo PDF com o horário completo. O arquivo será salvo na pasta Downloads com incremento automático de nome para evitar sobreposições de arquivos.

Contribuição
Faça um fork do repositório.
Crie uma branch para sua funcionalidade (git checkout -b minha-feature).
Commite suas alterações (git commit -m 'Adiciona nova funcionalidade').
Envie suas alterações (git push origin minha-feature).
Abra um Pull Request.
