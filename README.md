# API Instrutor
 API desenvolvida como trabalho, no curso Técnico em Desenvolvimento de Sistemas, usando NodeJS e o Express, com as requisições e respostas feitas através do Insomnia.

> Uma API para cadastro de instrutores e classes, verificação e deleção dos mesmos, ambos com verificações, atribuições e formatações.

### Requisitos

- [X] Deve ser possível cadastrar um instrutor
- [X] Deve ser possível cadastrar turmas
- [X] Deve ser possível vincular turmas ao instrutor
- [ ] Deve ser possível desvincular turmas ao instrutor
- [X] Deve ser possível buscar todos os instrutores
- [X] Deve ser possível buscar um instrutor pelo registro
- [X] Deve ser possível buscar um instrutor pelo cpf
- [X] Deve ser possível buscar um/vários instrutores pelo nome
- [X] Deve ser possível buscar todas as turmas
- [X] Deve ser possível buscar todas as turmas de um instrutor
- [X] Deve ser possível buscar uma turma de uma instrutor
- [X] Deve ser possível alterar o nome, e-mail, data de nascimento e telefone de um instrutor
- [X] Deve ser possível alterar (atualizar) a senha do instrutor
- [X] Deve ser possível deletar um instrutor
- [X] Deve ser possível deletar uma turma

### Regras de Negócio

- [X] Não deve ser possível cadastrar uma instrutor com registro já existente
- [X] Não deve ser possível cadastrar uma turma com o código já existente
- [X] Não deve ser possível buscar um instrutor não existente
- [X] Não deve ser possível buscar uma turma não existente
- [X] Não deve ser possível excluir um instrutor não existente
- [X] Não deve ser possível excluir uma turma não existente
- [X] Não deve ser possível excluir uma turma se esta estiver vinculada para algum instrutor
- [X] Não deve ser possível vincular a mesma turma para o mesmo instrutor

### Ajustes e melhorias

O projeto está concluído de acordo com os requisitos do trabalho, mas ainda em desenvolvimento com futuras atualizações, como objetivo de melhorar a API e obter mais conhecimento nos estudos em cima dela. As próximas atualizações serão voltadas para as seguintes tarefas:

- [x] Validação de CPF
- [x] Formatação de CPF 
- [x] Formatação de número de celular
- [ ] Criptografia de senha de login usando bcrypt

## 🤝 Colaboradores

Agradeço às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/thiagofqs">
        <img src="https://avatars.githubusercontent.com/u/39809188?v=4" width="100px;" alt="Foto do Thiago Freitas no GitHub"/><br>
        <sub>
          <b>Thiago Freitas</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/kaicgoncalves">
        <img src="https://avatars.githubusercontent.com/u/100730175?v=4" width="100px;" alt="Foto do Kaic Gonçalves no Github"/><br>
        <sub>
          <b>Kaic Gonçalves</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Maethsu">
        <img src="https://avatars.githubusercontent.com/u/108204887?v=4" width="100px;" alt="Foto do Matheus Armindo no Github (provisória)"/><br>
        <sub>
          <b>Matheus Armindo</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

### Professor
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/patrickviniciusestevao">
        <img src="https://avatars.githubusercontent.com/u/60794165?v=4" width="100px;" alt="Foto do Patrick Vinícius Estevão no GitHub"/><br>
        <sub>
          <b>Patrick Vinícius Estevão</b>
        </sub>
      </a>
    </td>
</table>

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE) para mais detalhes.

[⬆ Voltar ao topo](#)<br>
