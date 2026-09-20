# Contador de Graos V4.2

## Referencia metrica por zona conhecida
A tela possui REF 1 ativa por padrao no canto superior esquerdo. O quadrado fisico deve ficar inteiramente dentro dela.

O tamanho real e configuravel pelo usuario em milimetros. Exemplos: 30 mm, 50 mm, 75 mm. Use o slider ou campo numerico.

Fluxo:
1. Posicione o quadrado colorido dentro da REF 1.
2. Informe seu lado real em mm.
3. Clique CALIBRAR COR PELA ZONA REF 1. A cor dominante/saturada dentro da zona e aprendida.
4. Ative Debug da mascara. Branco deve representar o quadrado.
5. A deteccao usa somente componentes dentro da zona, com validacao geometrica tolerante.
6. Toda a zona REF ativa e removida da contagem de graos.

## Preparado para quatro referencias
REF 2, REF 3 e REF 4 ja existem nas configuracoes, desativadas. Em AJUSTAR ZONA DE REFERENCIA e possivel ativar e posicionar cada zona. A escala usa a mediana das referencias detectadas.

## GitHub Pages
Crie um repositorio, envie todos os arquivos desta pasta para a raiz, inclusive .github e src. Em Settings > Pages escolha GitHub Actions.
