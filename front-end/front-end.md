# Hi - Teste front-end

O teste consiste em avaliar suas habilidades em codar um front-end com react.
Foque em propor uma solução com um design de código bem elaborado e preparado para o crescimento da aplicação.

Vamos avaliar se seguiu os requisitos conforme solicitado.

Siga as instruções abaixo:

# O teste

O teste consiste em criar interfaces que possibilitem o usuário realize login e gerencie seus pacientes
essa gestão deve permitir a visualização dos dados em uma lista com a opção de inserir um novo paciente, editar ou excluir paciente existente.

Disponibilizamos o design da interface através do Figma [nesse link](https://www.figma.com/file/njMdC8jyJMyiFOIYpDsqzE/Hi-Teste?node-id=125%3A0). 
Através dele você poderá encontrar as definições de estilo como formas, cores, tamanhos e fontes.

Todos os assets podem ser exportados através do próprio figma. Toda a iconografia utilizada pode ser usada através do Fontawesome Free.

## Requisitos gerais

### *Projeto*

- Deve ser criado com React
- É permitido o uso de framework CSS (como Bootstrap, Material e outros)
- Atender requisitos de semântica
- A interface deverá ser responsiva e respeitar o design proposto
- Seu teste deverá estar documentado e sua versão final hospedada em algum lugar (como por exemplo Heroku)

### *Tela login*

- Botão "entrar" redireciona o usuário para a Lista de pacientes

### *Tela de Lista Pacientes*

- O campo de data de nascimento deverá respeitar o formato "DD/MM/AAAA"
- Enquanto não houver um paciente exibir uma mensagem "Nenhum Paciente cadastrado" 
- Ao clicar em excluir deverá exibir uma caixa de alerta solicitando confirmação de exclusão ex: "Tem certeza que deseja excluir?" 
- Ao clicar em editar redirecioná-lo para a tela de cadastro com os campos preenchidos
- A tabela deve exibir informações de pacientes passados que deverão ser consumidas de um JSON (modelo logo abaixo na seção API)

### *Tela Cadastro*

- Ao clicar em salvar, em caso de sucesso exibir mensagem de sucesso e encaminhar para tela de listagem
- Ao clicar em salvar, em caso de erro exibir mensagem de erro e permanecer na tela atual
- Validar os campos (Nome, Celular, Status e Data de Nascimento) como campos obrigatórios
- Incluir Datepicker no campo Data de Nascimento
- Incluir Máscaras nos campos (Celular, Data de Nascimento e CEP)

### *Geral*

- Queremos saber como você lida com consumo de conteúdo via request. Para isso, use nossos exemplos de JSON na seção **API** 
- Não precisa ser uma API sendo consumida por uma URL externa, indicamos que faça isso consumindo diretamente do JSON no projeto, porém, esperamos que toda a implementação de consumo desses dados sejam feitos da mesma forma que faria se estivesse consumindo externamente
- Use AJAX, axios, fetch o que achar melhor
- Não esperamos persistência desses dados em um Banco de Dados, porém, esperamos alguma persistência a nível de usuário


### *Diferencial*

- (Diferencial) - Sua aplicação pode estar bem embasada em performance web seguindo as boas práticas de https://web.dev/vitals/ um bom ranking no teste pode ser algo a mais: https://web.dev/measure/
- (Diferencial) - Acessibilidade: seguir as boas práticas


## API de exemplo sugerida

Na raiz do projeto [db](https://github.com/SaudeHi/hi-teste/blob/master) você encontra os arquivos db JSON a serem usados no projeto.

Pode consumi-la através do https://my-json-server.typicode.com/
Do qual nos permite a criação do endpoint fake com para testes
Link do endpoint https://my-json-server.typicode.com/SaudeHi/hi-teste

Exemplo:
```
GET / patient
https://my-json-server.typicode.com/SaudeHi/hi-teste/patient
```


## O que esperamos

- Os requisitos gerais cumpridos
- Responsividade
- Consistência de código
- Semântica
- Reuso de código
- Separação dos conceitos e responsabilidades
- Interface componentizável
- Atenção aos detalhes
- Testes unitários

## O que seria legal de ver mas não é obrigatório

- Micro interações fluídas
- Escreva no projeto um arquivo MD nos contando sobre suas decisões técnicas, as dificuldades que teve, funcionalidades e melhorias que implementaria caso fosse um projeto longa vida.

## Instruções

- Use o Git e hospede seu repositório no Github
- Faça commits separados de acordo com a evolução do seu teste, não faça 1 commit gigante ao final. Haja como se fosse um projeto real onde está trabalhando com mais pessoas
- Bem documentado, queremos saber o que instalar e como rodar, sem isso não é possível avaliar.


## Dúvidas

Quaisquer dúvidas procure nosso time para que possamos entrar em contato.

Boa sorte e bora codar! \o/

