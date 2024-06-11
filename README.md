## Projeto_ImersaoIA
# Problemas a solucionar e objetivos:
O acadêmico de medicina, ao longo da trajetória universitária, se depara com um curso completamente imerso na realidade da produção científica, da profissão baseada em evidências e , inderetamente, da ciência de dados. 
Como parte integral desta realidade, é exigido dele a contribuição da literatura científica; mas, com poucas oportunidades de participação em estudos maiores, como ensaios clínicos randomizados ou coortes, o aluno acaba tendo que procurar esta contribuição em uma forma mais acessível: A revisão sistemática.
A revisão sistemática, com metanálise ou não, é uma forma de sistematizar uma análise da literatura atual sobre determinado assunto, a partir de uma seleção de artigos científicos de alto impacto, que é muito mais do que a simples soma dos pontos que a compõem: Muitas revisões sistemáticas acabam contribindo com novos dados para a literatura científica, especialmente quando contam com uma metanálise e um bom conhecimento de ciência de dados.

Um empecilho, porém, é o arduo trabalho manual que é transferir os dados considerados relevantes para o ambiente de trabalho; especialmente quando consideramos as altas cargas horárias do curso de medicina. Com esta finalidade utilizamos o google colab, o gemini 1.5 e google IA studio.

# Algumas observações importantes:
Uma revisão sistemática é feita com muito mais do que dois artigos, como foi feita no projeto a seguir, e trabalha com um volume de dados muito maior. Este projeto é o arcabouço para esta automatização, pois a seleção completa de artigos a ser utilizados no tema escolhido pertence a um projeto que está a ser desenvolvido na minha universidade: a UFMG. 

# Como foi feito?: 
O padrão ouro para a realização de revisões sistemáticas é o protocolo prisma. Pedimos então ao gemini 1.5 para fazer o desenho do estudo com base no protocolo. Posteriormente, pedimos para analisar 2 artigos e, com base no desenho do estudo previamente fornecido, para retirar os dados estatisticamente significativos para o estudo.
Finalmente transformamos isto em tabela.

# Sobre o autor:
Sou um estudante da faculdade de medicina da UFMG com um grande paixão pela neurologia, pelas ciências exatas e suas aplicações em conjunto. Fui medalhista de ouro da olimpíada nacional de ciênicia de 2019 e sou membro na liga acadêmica de neurologia, neurocirurgia e neuroanatomia.
Atualmente estou aprendendo python na cisco network academy para complementar meus estudos em medicina, além de um curso do centro de inteligência artificial em saúde da UFMG sobre ciência de dados e python

* comando git push