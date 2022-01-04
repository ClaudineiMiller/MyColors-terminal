# MyColors-terminal
Projeto em python para imprimir fontes coloridas usando sequências de escape ANSI.

## Instruções de uso:
<ul>
  <li>Baixe o arquivo "myColorsTerminal.py" e coloque-o nas pasta do seu projeto.</li>
  <li>Faça a importação no seu projeto conforme abaixo, ou como preferir.</li>
</ul>
<p>from myColorsTerminal import FONT_Colors, BACKGROUND_Colors, RESET_colors</p>
<p>
ft = FONT_Colors()<br>
bg = BACKGROUND_Colors<br>
res = RESET_colors.reset<br>
</p>

### Exemplo de código 1:
print(f'{ft.cyan_e}Testando "myColorsTerminal"{res}') <br>
print(f'{bg.amarelo_c}{ft.vermelho_e}Testando "myColorsTerminal"{res}')

### Exemplo de código 2:
print( <br>
f""" <br>
{ft.magenta_e}{line_0}{res} <br>
     {ft.magenta_e}|{configTables["title"].center(line_1).upper()}|{res} <br>
{ft.magenta_e}{line_0}{res} <br>
""") <br>
    for sub in subtitles: <br>
        print( <br>
            f'''{ft.verde_c}{sub.center(calcCenterSubtitle).upper()}{res}''', end='|' <br>
            )
<figure>
  <img src="terminal.png" alt="Captura de tela do terminal">
  <figcaption>Captura de tela do terminal</figcaption>
</figure>            
