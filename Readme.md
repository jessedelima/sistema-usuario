[] Fazer uma API, que tenha as ações de CRUD de usuários. Será necessário salvar os campos de Nome, email, cpf, senha e foto;

[] As rotas de Deleção e atualização dos campos, devem estar protegidas por login. Utilizando JWT para proteger as rotas;

[] O campo de foto, deve ser armazenado em um bucket S3. Toda foto criada deve ser salva, quando atualizada, a mesma deve ser removida do bucket e criada a nova, referenciando no banco a nova;

[] Deverá ser utilizado o migrate e seed, para testar os conhecimentos de preenchimendo de dados dinânimos;

[] Utilizar algum metodo, para remover caracteres especiais nos número do CPF, exemplo: 115.225.616-50. Tem que salvar 11522561650; (use uma forma inteligênte para resolver isso);

[] Todas as rotas devem ser disponibilizadas no swagger;

[] Usar obrigatóriamente o NEST.JS e procure fazer o projeto na arquitetura segundo documentação.
