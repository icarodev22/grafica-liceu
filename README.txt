GRÁFICA E EDITORA LICEU — SITE (NOVA VERSÃO)

Arquivos:
- index.html: site completo (CSS e JS dentro do arquivo).
- assets/: fotos dos trabalhos e logotipos (logo-liceu-branco.png é a versão branca para fundo preto).

Para ver: abra index.html no navegador. As fontes (Bricolage Grotesque e DM Sans) vêm do Google Fonts; sem internet, o site usa Arial.

Como adicionar fotos novas:
1. Coloque a imagem (.webp ou .jpg, sem a faixa preta) na pasta assets/.
2. Abra index.html e procure "LISTA DE TRABALHOS" (perto do fim do arquivo).
3. Copie uma linha da lista e troque src, nome, alt e cats.
   - cats define os filtros: livros, cadernos, caixas, kits, folders.
   - Para criar um filtro novo, adicione uma linha em CATEGORIAS (logo abaixo, no script) e use a mesma chave em cats.
Os cards e os filtros se montam sozinhos a partir dessa lista.

WhatsApp: 81 99262-0120. Para mudar o número, troque 5581992620120 em index.html.

Imagens do topo (carrossel em loop): procure "IMAGENS DO TOPO" no index.html e edite a lista TOPO (ideal: 1080 x 1350).
