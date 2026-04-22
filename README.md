Para criar e renderizar a cena foi utilizado o programa Blender, normalmente usado para modelagem 3D. Como recomendado, usamos o cycles para a renderização com path tracing e EEVEE para a renderização em tempo real. Utilizando as configurações base, mudando apenas a renderização para utilizar a GPU ao inves da CPU. Na cena possui objetos de diferentes materiais, como metalico e emissivo misturados com luzes coloridas. 

Comparando os resultados de ambos os tipos de renderização nós coseguimos destacar o seguinte:

Iluminação indireta:
No path tracing, a luz se espalha de forma mais natural, iluminando melhor toda a cena. No tempo real, a iluminação é mais limitada e algumas áreas ficam mais "Chapadas".

Color Bleeding:
No path tracing, as cores do ambiente influenciam claramente os objetos, como o chão afetando o gato. No tempo real, esse efeito é mais fraco.

Reflexões:
O path tracing mostra reflexos mais realistas, até em superfícies não perfeitamente espelhadas. No tempo real, esses reflexos são quase inexistentes ou simplificados. O cálculo da reflexão então é calculado pela luz rebatida no objeto no path tracing enquanto no simplificada não há esse cálculo então o reflexo é limitado. 

Sombras:
No path tracing, as sombras são mais suaves e naturais. No tempo real, são mais duras e menos detalhadas.

Qualidade geral:
O path tracing produz uma imagem mais realista, enquanto o tempo real prioriza desempenho, sacrificando detalhes.

Referencia:
https://docs.blender.org/manual/en/2.91/render/cycles/index.html
Manual de Site oficial do Blender 

Feito por: Gabriel Assis Jaquet e Gabriel Siciliani Mendes de Oliveira
