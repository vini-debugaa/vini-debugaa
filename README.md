import pypandoc

content = r'''<h1 align="left">Vinícius Moreira Silva</h1>

<p>
  <strong><code>Estudante de Informática para Internet</code></strong>
</p>

<p>
  Olá! Me chamo Vinícius Moreira Silva, tenho 16 anos e curso o 2º ano do Ensino Médio integrado ao curso técnico de Informática para Internet. Sou interessado em tecnologia e desenvolvimento web e estou sempre buscando aprender, praticar e desenvolver novos projetos. Meu objetivo é crescer profissionalmente na área de TI e me tornar um desenvolvedor.
</p>

<p>
  <a href="https://github.com/vini-debugaa">
    <img src="https://img.shields.io/badge/GitHub-vini--debugaa-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <img src="https://img.shields.io/github/followers/vini-debugaa?style=for-the-badge&logo=github&label=Seguidores" alt="Seguidores">
</p>

<hr>

<h2>🤖 Linguagens e Tecnologias</h2>

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" alt="HTML, CSS e JavaScript">
</p>

<h2>📚 Atualmente estudando</h2>

<ul>
  <li>HTML e CSS</li>
  <li>Lógica de programação</li>
  <li>JavaScript</li>
  <li>Desenvolvimento Web</li>
</ul>

<h2>🎯 Objetivos</h2>

<ul>
  <li>Desenvolver projetos próprios</li>
  <li>Aprender novas tecnologias</li>
  <li>Construir meu portfólio</li>
  <li>Evoluir como desenvolvedor</li>
</ul>

<hr>

<p align="center"><em>🚀 Um passo de cada vez. Sempre aprendendo!</em></p>
'''

output_path = "/mnt/data/README_Vinicius_estilo_referencia.md"
pypandoc.convert_text(content, "md", format="html", outputfile=output_path, extra_args=["--standalone"])
print(output_path)
