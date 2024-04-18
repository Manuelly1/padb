# Resumo ODBC
ODBC (Open Database Connectivity) é uma API padronizada da indústria que permite que aplicativos acessem e manipulem dados em diferentes bancos de dados utilizando a linguagem de consulta estruturada - SQL. O ODBC funciona como uma camada de abstração entre o aplicativo e o banco de dados subjacente, ele possibilita que desenvolvedores escrevam código independente do banco de dados específico. Para utilizar o ODBC em Python, o primeiro passo é estabelecer uma conexão com o banco de dados através do método `pyodbc.connect()`, fornecendo os detalhes de conexão necessários. Em seguida, cria-se um cursor para executar consultas SQL e manipular os resultados conforme necessário. Após a conclusão das operações desejadas, é importante confirmar as alterações e, por fim, fechar tanto a conexão quanto o cursor para liberar recursos do sistema.

# Resumo ORM
ORM (Object-Relational Mapping) é uma técnica de programação que permite aos desenvolvedores manipular bancos de dados relacionais utilizando objetos de programação em vez de consultas SQL diretamente. Essa técnica mapeia os objetos de uma aplicação para as tabelas de um banco de dados, automatizando a conversão entre dados armazenados em tabelas e objetos no código.

A biblioteca SQLAlchemy em Python é uma ferramenta ORM poderosa que simplifica consideravelmente a manipulação de bancos de dados relacionais. Com o SQLAlchemy, os desenvolvedores podem definir modelos de dados como classes Python e interagir com o banco de dados através desses modelos. A biblioteca cuida automaticamente da tradução entre objetos Python e as instruções SQL necessárias para operar nos dados armazenados.

Ao empregar o ORM do SQLAlchemy, os desenvolvedores podem definir modelos de dados usando classes, mapeá-los para tabelas no banco de dados, executar consultas e manipular dados usando métodos e expressões SQLAlchemy, além de gerenciar transações eficientemente. Isso simplifica significativamente o desenvolvimento de aplicativos, torna o código mais portátil e reduz a necessidade de escrever SQL manualmente.

# Scripts
