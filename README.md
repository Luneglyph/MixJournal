# MixJournal
Aplicação de registro de álbuns musicais.

**Introdução – explicando o tema do projeto**

A aplicação **MixJournal** visa criar uma plataforma de uso individual focada no registro de álbuns musicais ouvidos pelo usuário, funcionando como um diário pessoal de experiências musicais.

Nela, o usuário poderá registrar seus álbuns favoritos, atribuir notas gerais, escrever e editar *reviews*, além de adicionar palavras-chave para cada álbum.

Também será possível acessar uma tela de feedback, onde o usuário visualizará gráficos simples sobre gêneros, artistas e álbuns mais frequentes, bem como uma visão geral das palavras-chave mais utilizadas.

Os gráficos serão implementados com a biblioteca **Matplotlib**, utilizando visualizações em barras ou pizza, com dados como gêneros mais ouvidos e artistas mais bem avaliados.

A persistência dos dados será feita localmente por meio do MongoDB, garantindo que os registros sejam mantidos entre sessões.

**Objetivos (geral e específicos em ordem de prioridade)**

A aplicação proposta visa criar um sistema para avaliação e organização de álbuns musicais. O sistema permitirá:

- **Registrar álbuns musicais** com informações completas;
- **Adicionar dados como**: nome do artista, ano de lançamento, gênero musical, nota geral, review textual e palavras-chave;
- **Visualizar gráficos estatísticos** com tendências de escuta do usuário (como gêneros mais ouvidos, artistas mais bem avaliados e palavras mais recorrentes);
- *(Opcional, caso haja tempo)*: exportar um registro individual em formato **PNG** com as informações do álbum estilizadas para compartilhamento.

**Telas previstas**

1. **Biblioteca de registros**

Tela principal onde os álbuns registrados são exibidos com miniaturas e dados resumidos. Nesta tela será possível:

- Editar ou apagar um registro existente;
- Filtrar a exibição por:
    - Data de registro;
    - Ordem alfabética (A–Z ou Z–A);
    - Artista (agrupar por artista);
    - Nota (ordem crescente ou decrescente).

2. **Novo registro**

Tela para cadastrar um novo álbum. Os campos serão:

- Nome do álbum;
- Nome do artista;
- Upload de imagem para miniatura (opcional);
- Gêneros musicais;
- Ano de lançamento;
- Lista de faixas (campo de texto livre);
- Nota geral do álbum;
- Review textual;
- Palavras-chave (opcional).

3. **Tela de gráficos**

Tela que exibirá visualizações estatísticas com base nos dados cadastrados. Os gráficos incluirão:

- Gênero mais ouvido;
- Artista mais bem avaliado;
- Palavras-chave mais utilizadas;
- Outros dados relevantes conforme disponibilidade.
