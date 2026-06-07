COMO SUBIR NA VERCEL SEM ERRO 404

1) Extraia este ZIP.
2) No GitHub, os arquivos index.html, vercel.json, as pastas css, js, images, fonts e media precisam ficar na RAIZ do repositório.
   Certo: /index.html
   Errado: /nome-da-pasta/index.html
3) Suba tudo no GitHub.
4) Na Vercel, importe esse repositório.
5) Em Framework Preset, selecione Other.
6) Build Command: deixe vazio.
7) Output Directory: deixe vazio ou coloque .
8) Deploy.

OBS: Os vídeos da pasta media foram otimizados para ficarem abaixo de 100 MB, porque GitHub costuma rejeitar arquivos grandes acima desse limite.
