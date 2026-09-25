# Histórias do usuário

## História de Usuário — Exemplo a se seguir!!!

### Persona

**Mariana Oliveira — Gestora da Rede de Ensino**

### Requisito funcional

O sistema deve permitir visualizar, comparar e analisar os dados das escolas da rede, possibilitando também a exportação de relatórios consolidados.

### História de usuário

**Como gestora da rede de ensino, quero visualizar e comparar os resultados das escolas em um painel consolidado, para analisar os dados da rede e tomar decisões estratégicas de forma mais rápida e eficiente.**

### Critérios de aceitação

* Deve permitir visualizar os resultados das escolas da rede.
* Deve permitir comparar os dados entre diferentes escolas.
* Deve apresentar os dados de forma simples e organizada.
* Deve permitir analisar os resultados para apoiar decisões estratégicas.
* Deve permitir gerar e exportar relatórios consolidados da rede.
* Os relatórios devem reunir os dados das escolas selecionadas.
* Os dados apresentados devem corresponder aos resultados registrados no sistema.

### Benefício esperado

Reduzir o tempo necessário para analisar os dados e gerar relatórios assim facilitando decisões mais rápidas e eficientes sobre a rede de ensino.

---


# Histórias de Usuário — Persona 2

## Persona 2 — Carla Mendes

**Perfil:** Professora de Matemática

---

## S1 — Extração e revisão de questões

### Requisito funcional

O sistema deve permitir extrair automaticamente questões de provas em PDF e oferecer uma interface de revisão rápida do conteúdo extraído.

### História de usuário

**Como professora de matemática, quero extrair questões de provas antigas em PDF e revisar rapidamente o que foi extraído, para montar avaliações sem precisar redigitar as questões manualmente.**

### Critérios de aceitação

* Deve permitir importar arquivos em PDF para extração de questões.
* Deve extrair automaticamente o texto e as alternativas das questões do PDF.
* Deve apresentar uma interface de revisão rápida do conteúdo extraído.
* Deve permitir confirmar a questão extraída sem necessidade de redigitação.
* Deve permitir corrigir manualmente um trecho da extração quando necessário.
* Deve sinalizar quando uma extração apresentar baixa confiabilidade.

---


## S2 — Dashboards de desempenho

### Requisito funcional

O sistema deve apresentar dashboards que identifiquem as habilidades ou descritores críticos de cada aluno com base nos resultados das avaliações.

### História de usuário

**Como professora de matemática, quero visualizar em que habilidade ou descritor cada aluno apresenta dificuldade, para identificar a tempo quem precisa de reforço.**

### Critérios de aceitação

* Deve apresentar o desempenho de cada aluno por habilidade ou descritor, não apenas a nota final.
* Deve destacar os alunos com maior necessidade de reforço.
* Deve permitir visualizar o desempenho individual e o desempenho da turma.
* Os dados exibidos devem corresponder aos resultados registrados no sistema após a aplicação da avaliação.
* Deve atualizar o dashboard automaticamente após a correção das avaliações.

# Histórias de Usuário — Persona 5

## Persona 5 — Camila Ferreira

**Perfil:** Professora com permissão de Revisão de Questões

---

## S1 — Revisão lado a lado do documento original e da questão extraída

### Requisito funcional

O sistema deve apresentar uma interface de revisão lado a lado, comparando o documento original com a questão extraída.

### História de usuário

**Como professora com permissão de revisão, quero comparar lado a lado o documento original e a questão extraída, para confirmar que a extração capturou tudo corretamente antes de aprovar.**

### Critérios de aceitação

* Deve exibir o documento original e a questão extraída lado a lado.
* Deve indicar a página de origem correspondente à questão.
* Deve destacar os campos com baixa confiança na extração.
* Deve permitir navegar entre as questões extraídas do mesmo documento.
* Deve permitir ampliar a visualização de imagens, gráficos ou tabelas do documento original.


---

## S2 — Correção e aprovação da questão extraída

### Requisito funcional

O sistema deve permitir editar o enunciado, as alternativas, o gabarito e as imagens de uma questão extraída, impedindo a aprovação de questões incompletas.

### História de usuário

**Como professora com permissão de revisão, quero corrigir o enunciado, as alternativas, o gabarito e as imagens de uma questão extraída, para garantir que ela esteja correta antes de entrar no Banco de Questões.**

### Critérios de aceitação

* Deve permitir editar o enunciado e as alternativas da questão extraída.
* Deve permitir corrigir o gabarito quando estiver incorreto.
* Deve permitir ajustar ou substituir a imagem associada à questão.
* Não deve permitir aprovar uma questão sem gabarito ou sem habilidade/descritor associado.
* Deve confirmar a aprovação apenas após a validação de todos os campos obrigatórios.

## S3 — Rastreabilidade da aprovação

### Requisito funcional

O sistema deve registrar o responsável pela aprovação de cada questão e manter o histórico de alterações realizadas durante a revisão.

### História de usuário

**Como professora com permissão de revisão, quero que o sistema registre quem revisou e aprovou cada questão, para manter a rastreabilidade do processo.**

### Critérios de aceitação

* Deve registrar o usuário responsável pela aprovação da questão.
* Deve registrar a data e a hora da aprovação.
* Deve manter o histórico das alterações feitas durante a revisão.
* Deve permitir consultar o histórico de uma questão aprovada.
* As informações de rastreabilidade não devem poder ser editadas após o registro.


# Histórias de Usuário — Persona 6

## Persona 6 — Ricardo Nascimento

**Perfil:** Administrador da Instituição

---

## S1 — Gerenciamento de usuários

### Requisito funcional

O sistema deve permitir ao administrador cadastrar, editar e remover usuários, além de definir seus perfis e permissões de acesso.

### História de usuário

**Como administrador da instituição, quero gerenciar os usuários, seus perfis e permissões de acesso, para manter os cadastros organizados e garantir que cada pessoa tenha acesso adequado às funcionalidades do sistema.**

### Critérios de aceitação

* Deve permitir cadastrar usuários.
* Deve permitir editar os dados dos usuários.
* Deve permitir definir o perfil e as permissões de cada usuário.
* Deve permitir conceder a permissão de Revisão de Questões aos professores designados.
* Deve impedir a exclusão de usuários que possuam registros vinculados.
* Deve informar o motivo quando uma exclusão for impedida.
* Deve permitir excluir usuários quando não houver registros vinculados.
* Cada usuário deve acessar somente as funcionalidades autorizadas para seu perfil.

---

## S2 — Importação de usuários por CSV

### Requisito funcional

O sistema deve permitir ao administrador cadastrar vários usuários por meio da importação de um arquivo CSV.

### História de usuário

**Como administrador da instituição, quero importar vários usuários por meio de um arquivo CSV, para reduzir o tempo necessário para cadastrar novos usuários em uma instituição com muitos alunos.**

### Critérios de aceitação

* Deve permitir importar um arquivo CSV.
* O arquivo deve seguir o padrão exigido pelo sistema.
* Deve permitir importar dados como nome, e-mail, data de nascimento e papel.
* Deve informar os erros encontrados durante a importação.
* Os usuários válidos devem ser cadastrados após a importação.
* O sistema não deve cadastrar usuários com dados inválidos.

## S3 — Geração de QR Codes e carteirinhas
### Requisito funcional

O sistema deve permitir ao administrador gerar QR Codes e carteirinhas dos estudantes cadastrados.

### História de usuário

**Como administrador da instituição, quero gerar QR Codes e carteirinhas para os estudantes cadastrados, para facilitar sua identificação e manter seus registros organizados.**

### Critérios de aceitação
* Deve permitir gerar um QR Code para o estudante cadastrado.
* Deve permitir gerar a carteirinha do estudante.
* Os dados da carteirinha devem estar relacionados ao estudante correto.
* O QR Code deve estar associado ao estudante correspondente.
* A geração deve utilizar os dados cadastrados no sistema.

# Histórias de Usuário — Persona 2

## Persona 2 — Carla Mendes

**Perfil:** Professora de Matemática

---

## S1 — Extração e revisão de questões

### Requisito funcional

O sistema deve permitir extrair automaticamente questões de provas em PDF e oferecer uma interface de revisão rápida do conteúdo extraído.

### História de usuário

**Como professora de matemática, quero extrair questões de provas antigas em PDF e revisar rapidamente o que foi extraído, para montar avaliações sem precisar redigitar as questões manualmente.**

### Critérios de aceitação

* Deve permitir importar arquivos em PDF para extração de questões.
* Deve extrair automaticamente o texto e as alternativas das questões do PDF.
* Deve apresentar uma interface de revisão rápida do conteúdo extraído.
* Deve permitir confirmar a questão extraída sem necessidade de redigitação.
* Deve permitir corrigir manualmente um trecho da extração quando necessário.
* Deve sinalizar quando uma extração apresentar baixa confiabilidade.

---


## S2 — Dashboards de desempenho

### Requisito funcional

O sistema deve apresentar dashboards que identifiquem as habilidades ou descritores críticos de cada aluno com base nos resultados das avaliações.

### História de usuário

**Como professora de matemática, quero visualizar em que habilidade ou descritor cada aluno apresenta dificuldade, para identificar a tempo quem precisa de reforço.**

### Critérios de aceitação

* Deve apresentar o desempenho de cada aluno por habilidade ou descritor, não apenas a nota final.
* Deve destacar os alunos com maior necessidade de reforço.
* Deve permitir visualizar o desempenho individual e o desempenho da turma.
* Os dados exibidos devem corresponder aos resultados registrados no sistema após a aplicação da avaliação.
* Deve atualizar o dashboard automaticamente após a correção das avaliações.




