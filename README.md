# Mathplotlib

Criada em 2003 por John Hunter, a Matplotlib é uma biblioteca gratuita para a criação de gráficos e visualização de dados, feita para a linguagem Python, inspirada no Matlab.

O `pyplot` é um dos módulos da Matplotlib. É ela que gera os gráficos propriamente ditos. Mas há outros, como o `ticker`.

### Instalação

As instruções para sua instalação estão no site da biblioteca:

https://matplotlib.org/stable/users/installing.html

Mas é comum que já venha instalada nas distribuições populares do Python, como Anaconda, ActivePython e WinPython.

### Lógicas 

O Matplotlib possui duas lógicas para a geração de gráficos:

Lógica <b>"Object-oriented"</b>: essa é a recomendada e a que será usada nesse tutorial<br>
`fig, ax = plt.subplots()  
ax.plot([1, 2, 3, 4], [1, 4, 2, 3])`

Lógica <b>"State-based"</b>: usa a lógica de "ponteiros"<br>
`plt.plot([1, 2, 3, 4], [1, 4, 2, 3])`

É muito importante compreender essas duas lógicas, devendo-se dar preferência à primeira. A existência dessas duas lógicas dá margem a muita confusão. Quando se pesquisa na internet sobre recursos da Mathplolib por vezes aparece uma lógica, por vezes outra. É preciso saber diferenciá-las

Aqui há mais explicações sobre isso:

https://towardsdatascience.com/plt-subplot-or-plt-subplots-understanding-state-based-vs-object-oriented-programming-in-pyplot-4ba0c7283f5d<br>
https://matplotlib.org/matplotblog/posts/pyplot-vs-object-oriented-interface/<br>
https://matplotlib.org/stable/tutorials/introductory/lifecycle.html<br>

### Artistas

Um gráfico do Matplotlib contém elementos chamados de <b>"Artists"</b>. Os mais importantes são:

<b>Figure</b><br>
https://matplotlib.org/api/figure_api.html<br>
O objeto "Figure" contém a imagem geral do gráfico e todos os elementos de plotagem.

<b>Axes</b><br>
https://matplotlib.org/api/axes_api.html<br>
O objeto "Axes" contém o gráfico, pois uma "Figure" pode ter mais de um "Axes" (gráfico)

<b>Axis</b><br>
https://matplotlib.org/api/axis_api.html<br>
O objeto "Axis" representa os eixos (X e Y) do gráfico


Aqui há um bom texto explicativo:

https://dev.to/skotaro/artist-in-matplotlib---something-i-wanted-to-know-before-spending-tremendous-hours-on-googling-how-tos--31oo


### Saiba mais

Veja mais informações e tutoriais sobre a Mathplotlib em:

https://www.w3schools.com/python/matplotlib_intro.asp  
https://www.tutorialspoint.com/matplotlib/
