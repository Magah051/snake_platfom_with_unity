# Snake Platfom Project

<i>Este é um pequeno projeto contendo uma cena de jogo simulando o comportamento de uma cobra saltando plataformas feito em C# com a engine Unity. Diversos conceitos foram aplicados aqui, dentre eles:
- Uso de colisores
- Uso de Física 2D (Circle Collider)
- Trail Renderer
</i>  
<hr>

## Detalhes do Recurso
O Trail Renderer é um componente no Unity, um motor de jogo amplamente utilizado, que permite criar trilhas ou rastros de objetos em movimento. Esse componente é especialmente útil para criar efeitos visuais, como trilhas de partículas, rastros de luz, rastros de projéteis e muito mais. Ele é frequentemente usado para adicionar um senso de movimento e dinamismo a objetos em cena.

- Adicionar o Trail Renderer:Para usar o Trail Renderer em um objeto, você deve primeiro adicionar esse componente a ele. Isso pode ser feito selecionando o objeto no painel Hierarchy, indo para a aba "Inspector" e clicando em "Add Component". Em seguida, procure por "Trail Renderer" e adicione-o ao objeto.
- Configurar as Propriedades: Após adicionar o Trail Renderer, você pode configurar suas propriedades no painel Inspector para controlar o visual e o comportamento do rastro.
Time: Determina o tempo que os pontos do rastro permanecerão visíveis antes de desaparecerem.
Start Width e End Width: Controlam a largura do rastro no início e no fim.
Material: Define o material que será aplicado ao rastro, afetando sua aparência.
Color: Define a cor do rastro.
Min Vertex Distance: Controla a distância mínima entre os vértices do rastro. Quanto menor o valor, mais suave o rastro será.
- Criar Rastros: Com o Trail Renderer configurado, quando o objeto se mover na cena, ele deixará um rastro atrás de si, que gradualmente desvanecerá de acordo com as propriedades definidas. Quanto mais rápido o objeto se mover, mais longo e suave será o rastro.
- Ajustar e Testar: Dependendo do efeito visual desejado, você pode precisar ajustar as propriedades do Trail Renderer para obter o resultado desejado. Isso pode incluir ajustar a largura, a duração do rastro e a distância entre os vértices.

## Instalação
Este jogo não há a necessidade de instalação. Baixe no link disponível, extraia a pasta e clique no arquivo `SnakePlatform.exe` e jogue a vontade!

## Como Testar?
- Basta usar ao mouse quando a bolinha colidir com alguma plataforma. 

## Interface do Jogo
![ezgif-4-b17f7b06cc](https://github.com/Magah051/snake_platfom_with_unity/assets/31749933/5de9f5fd-5c90-4913-a432-2454de416807)
