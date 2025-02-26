** Funcionalidades
Tela de Login e Cadastro:
Login com validação de email e senha.
Cadastro com confirmação de senha.
Feedback em tempo real nos campos de entrada.
Persistência do nome de usuário via localStorage.
Página Inicial (index.html):
Carrosséis de filmes populares, em alta e lançamentos.
Mensagem de boas-vindas após login.
Header com navegação, perfil do usuário e botão de logout.
Página de Séries (series.html):
Carrosséis de séries populares, em alta e lançamentos.
Navegação consistente com a página inicial.
Design Responsivo: Interface escura inspirada no Netflix, com transições suaves e carrosséis interativos.
API TMDB: Integração para buscar dados de filmes e séries em tempo real.
Pré-requisitos
Navegador moderno (Chrome, Firefox, etc.).
Conexão à internet para carregar dados da API TMDB.
Chave de API do TMDB (obtenha em https://www.themoviedb.org/).
Instalação
Clone o repositório:
bash
Wrap
Copy
git clone https://github.com/seu-usuario/netflix-clone.git
cd netflix-clone
Obtenha uma chave da API TMDB:
Crie uma conta no TMDB.
Vá para "Configurações" > "API" e gere uma chave.
Copie a chave fornecida.
Configure a chave da API:
Abra os arquivos index.html e series.html.
Substitua 'SUA_CHAVE_API_AQUI' pela sua chave do TMDB em ambos os arquivos:
javascript
Wrap
Copy
const API_KEY = 'SUA_CHAVE_API_AQUI';
Abra o projeto:
Coloque os arquivos (index.html, series.html, styles.css) em uma pasta.
Abra index.html em um navegador (pode usar uma extensão como "Live Server" no VS Code para melhor experiência).
Uso
Tela de Login/Cadastro:
Ao abrir index.html, você verá a tela de login.
Use um email válido (ex.: exemplo@dominio.com) e uma senha com pelo menos 4 caracteres.
Clique em "Assine agora" para cadastrar uma nova conta.
Após login ou cadastro, você será levado à página inicial.
Explorar Conteúdo:
Na página inicial (index.html), veja filmes em carrosséis.
Clique em "Séries" no header para ir a series.html e explorar séries.
Passe o mouse sobre os itens para ver botões de "Play" e "Minha Lista" (não funcionais por enquanto).
Logout:
Clique em "Sair" no header para voltar à tela de login.
Estrutura do Projeto
text
Wrap
Copy
netflix-clone/
├── index.html      # Página inicial com login, cadastro e filmes
├── series.html     # Página dedicada a séries
├── styles.css      # Estilos compartilhados entre as páginas
└── README.md       # Este arquivo
Tecnologias Utilizadas
HTML5: Estrutura das páginas.
CSS3: Estilização e animações.
JavaScript: Lógica de interação e integração com a API TMDB.
TMDB API: Fonte de dados para filmes e séries.
Limitações e Possíveis Melhorias
Autenticação Simulada: Não há backend; o login/cadastro é apenas frontend.
Botões Interativos: "Play" e "Minha Lista" não têm funcionalidade real.
Páginas Adicionais: Faltam páginas para "Filmes" e "Documentários".
Busca: Não há funcionalidade de busca por títulos.
Responsividade: Pode ser otimizada para dispositivos móveis.
Para adicionar essas melhorias, considere integrar um backend (como Node.js com Express) ou expandir o JavaScript.

Contribuição
Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias! Sugestões são bem-vindas.

Licença
Este projeto é de uso livre para fins educacionais. A API TMDB tem seus próprios termos de uso; consulte-os em https://www.themoviedb.org/documentation/api/terms-of-use.
