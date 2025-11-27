## Modelagem de Banco de Dados - Turismo

Projeto com código SQL, dicionário de dados, modelo conceitual, modelo lógico e PDF com delete, update e insert.

| Tabelas | Colunas |
| ----------- | ----------- |
|cidade|id_cidade, nome, estado, pais|
|evento|id_evento, nome, preco|
|cidade_evento|id_cidade_evento, data_, hora, id_cidade, id_evento|
|ponto_turistico|id_ponto, nome, endereco, preco, classificacao, descricao, id_cidade|
|hotel|id_hotel, nome, endereco, classificacao, id_cidade|
|servico_turistico|id_servico, nome, endereco, id_cidade, id_tipo|
|tipo|id_tipo, descricao, preco|

---

### Modelo conceitual
Feito com o uso do software BRModelo, mostrando o relacionamento de cada tabela e seus atributos no diagrama ER.

---

### Dicionário de Dados
O dicionário de dados descreve detalhadamente as tabelas, seus campos, tipos de dados, tamanhos e restrições (como chaves primárias e estrangeiras).

---

### Modelo Lógico
O modelo lógico (arquivo Modelo lógico - Turismo.pdf) lista as tabelas e suas colunas, explicitando as relações de Chave Estrangeira (FK).

Relações Chave-Estrangeira (FK):

* cidade_evento referencia cidade e evento.
* ponto_turistico referencia cidade.
* hotel referencia cidade.
* servico_turistico referencia cidade e tipo\_servico.

---

### Código SQL
O arquivos SQL contém comandos para:
* Criação do esquema (turismo).
* Criação de todas as tabelas (utilizando PRIMARY KEY e REFERENCES para as chaves primárias e estrangeiras).
* Inserção inicial das tabelas com colunas de exemplo sobre cidades brasileiras, eventos, pontos turísticos, hotéis e serviços.
* O script inclui dados de 5 cidades e informações relacionadas para cada tabela, tendo como FK a tabela cidade.
