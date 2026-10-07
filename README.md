# choliba.github.io

Site da documentação do [choliba](https://github.com/choliba/choliba): <https://choliba.github.io/>.

O conteúdo vem de `docs/` no repositório `choliba/choliba`. Este repositório só publica: a cada release
(push na `master` de lá), um `repository_dispatch` dispara o workflow aqui, que clona o código, gera o
VitePress e faz o deploy no GitHub Pages.
