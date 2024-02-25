<html>
<head>  </head>

<body>
  <div>
    <h3 align="center"> 
      <img align="center" alt="Kotlin" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" />
     "IMC APP"
      <img align="center" alt="Kotlin" height="80" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kotlin/kotlin-original-wordmark.svg" />
    </h3>    
    
##
<div align="justify">
  
<h4>MainActivity:</h4>
Esta é a classe principal da atividade do Android. No método onCreate, ele configura o conteúdo da atividade para ser a função IMCAppTheme, que por sua vez envolve a função Surface,
exibindo a tela principal do aplicativo (IMCScreen).

<h4>IMCScreen:</h4>
Esta função é responsável por criar a interface do usuário da tela principal do aplicativo.
Usa o Compose, um framework declarativo para criar interfaces de usuário no Android.
Usa uma instância de remember para manter o estado do peso (peso), altura (altura), índice de massa corporal (imc), e a classificação do IMC (statusImc).

<h4>Box e Column:</h4>
Box e Column são componentes do Compose usados para organizar e posicionar outros componentes na tela.
A Column principal tem dois blocos: o cabeçalho (header) e o formulário.

<h4>Header:</h4>
Um cabeçalho que contém um título, uma imagem (logo) e um espaçamento. Usa um fundo vermelho (colorResource(id = R.color.vermelho_fiap)).

<h4>Formulário:</h4>
Um formulário contendo dois campos de entrada (OutlinedTextField) para peso e altura, respectivamente.
Um botão "CALCULAR" que aciona a função calcularIMC com os valores inseridos e exibe o resultado na parte inferior da tela.

<h4>Card de Resultado:</h4>
Um Card na parte inferior da tela que exibe o resultado do cálculo do IMC.
Usa um Row para exibir o status do IMC (statusImc) e o valor calculado do IMC (imc.value).

##
<p>:star:Em resumo, o aplicativo é uma calculadora de IMC que recebe o peso e a altura do usuário, calcula o IMC e exibe o resultado na tela, incluindo uma classificação do
estado de saúde com base no IMC. O design é feito usando o framework Compose, e elementos visuais como cores e formas são configurados por meio de recursos definidos
em arquivos de recursos (res).</p>
