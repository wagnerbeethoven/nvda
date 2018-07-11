<h1>
    Referência Rápida de Comandos do NVDA 2018.2</h1>

<h2>Começando com o NVDA</h2>
<h3>Gestos de Toques do NVDA</h3>
<h4>Modos de Toques</h4>
<p>
    Para alternar entre os modos de toque, execute um toque com 3 dedos.
</p>
<h3>Comandos Básicos do NVDA</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de desktop</th>
            <th>Tecla de laptop</th>
            <th>Toque [Gesto]</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Parar a voz</td>
            <td>Control</td>
            <td>Control</td>
            <td>Toque com dois dedos</td>
            <td>Para instantaneamente a voz</td>
        </tr>
        <tr>
            <td>Pausar a voz</td>
            <td>Shift</td>
            <td>Shift</td>
            <td>nenhum</td>
            <td>Pausa instantaneamente a voz. Pressionada novamente continuará a falar desde onde parou (se a pausa for suportada
                pelo sintetizador atual)</td>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>NVDA+n</td>
            <td>NVDA+n</td>
            <td>Duplo toque com 2 dedos</td>
            <td>Abre o Menu do NVDA para permitir que você acesse preferências, ferramentas, ajuda, etc.</td>
        </tr>
        <tr>
            <td>Alternar Modo de Fala</td>
            <td>NVDA+s</td>
            <td>NVDA+s</td>
            <td>nenhum</td>
            <td>Alterna o modo de fala entre fala, bipe e desativado.</td>
        </tr>
        <tr>
            <td>Alternar Modo Ajuda de Entrada</td>
            <td>NVDA+1</td>
            <td>NVDA+1</td>
            <td>nenhum</td>
            <td>Ao pressionar qualquer tecla neste modo, será informada a tecla e a descrição de qualquer comando do NVDA associado
                com ela</td>
        </tr>
        <tr>
            <td>Encerrar o NVDA</td>
            <td>NVDA+q</td>
            <td>NVDA+q</td>
            <td>nenhum</td>
            <td>Sai do NVDA</td>
        </tr>
        <tr>
            <td>Passar a próxima tecla</td>
            <td>NVDA+f2</td>
            <td>NVDA+f2</td>
            <td>nenhum</td>
            <td>Informa ao NVDA para deixar passar a próxima tecla pressionada para a aplicação ativa, mesmo que seja normalmente
                tratada como uma tecla de comando do NVDA</td>
        </tr>
        <tr>
            <td>Alternar ativação do Modo Dormir em um aplicativo</td>
            <td>NVDA+shift+s</td>
            <td>NVDA+shift+z</td>
            <td>nenhum</td>
            <td>O modo dormir desabilita todos os comandos de teclado do nvda e a saída de voz/braille para o aplicativo atual.
                Isso é muito útil em programas com voz própria ou recurso de leitura de telas. Pressione este comando novamente
                para desativar o modo dormir.</td>
        </tr>
    </tbody>
</table>

<a name="ReportingSystemInformation"></a>
<h3>Anunciando Informações do Sistema</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Anunciar data/hora</td>
            <td>NVDA+f12</td>
            <td>Pressionando uma vez, anuncia a hora atual, duas vezes, anuncia a data</td>
        </tr>
        <tr>
            <td>Anunciar o estado da bateria</td>
            <td>NVDA+shift+b</td>
            <td>Anuncia o estado da bateria, ou seja, se a energia CA [corrente alternada] está em uso ou a porcentagem atual
                da carga.</td>
        </tr>
        <tr>
            <td>Anunciar o Texto na Área de Transferência</td>
            <td>NVDA+c</td>
            <td>Anuncia o Texto na área de transferência se houver algum.</td>
        </tr>
    </tbody>
</table>

<h2>Navegando com o NVDA</h2>
<h3>Navegando com o Foco do Sistema</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de desktop</th>
            <th>Tecla de laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Informar o foco atual</td>
            <td>NVDA+tab</td>
            <td>| NVDA+tab</td>
            <td>Anuncia o objeto atual ou controle que tem o foco do sistema. Ao pressionar duas vezes soletrará a informação</td>
        </tr>
        <tr>
            <td>Anunciar o título</td>
            <td>NVDA+t</td>
            <td>NVDA+t</td>
            <td>Anuncia o título da janela atualmente em execução. Ao pressionar duas vezes soletrará a informação. Três vezes
                copiará o conteúdo para a área de transferência</td>
        </tr>
        <tr>
            <td>Ler janela ativa</td>
            <td>NVDA+b</td>
            <td>NVDA+b</td>
            <td>Lê todos os controles na janela atual em execução (muito útil para diálogos)</td>
        </tr>
        <tr>
            <td>Ler a Barra de Status</td>
            <td>NVDA+end</td>
            <td>NVDA+shift+end</td>
            <td>Lê a barra de status caso o NVDA a encontre. Este comando também move a navegação de objetos para sua localização.
                Pressionando-se duas vezes, soletrará a informação. Pressionando três vezes copiará para a área de transferência</td>
        </tr>
    </tbody>
</table>

<h3>Navegando com o Cursor do Sistema</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de desktop</th>
            <th>Tecla de laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Leitura contínua</td>
            <td>NVDA+seta abaixo</td>
            <td>NVDA+a</td>
            <td>Inicia a leitura a partir da posição atual do cursor do sistema, movendo-o pelo texto</td>
        </tr>
        <tr>
            <td>Ler linha atual</td>
            <td>NVDA+seta acima</td>
            <td>NVDA+l</td>
            <td>Lê a linha onde o cursor do sistema está posicionado atualmente. Ao pressionar duas vezes soletra a linha. Pressionando-se
                três vezes, soletra-a usando descrições de caracteres.</td>
        </tr>
        <tr>
            <td>Ler texto atualmente selecionado</td>
            <td>NVDA+Shift+seta acima</td>
            <td>NVDA+shift+s</td>
            <td>Lê qualquer texto selecionado atualmente</td>
        </tr>
        <tr>
            <td>Próxima Sentença</td>
            <td>alt+seta abaixo</td>
            <td>alt+seta abaixo</td>
            <td>Move o cursor do sistema para a próxima sentença e a anuncia. (suportado apenas no Microsoft Word e Outlook)</td>
        </tr>
        <tr>
            <td>Sentença anterior</td>
            <td>alt+seta acima</td>
            <td>alt+seta acima</td>
            <td>Move o cursor do sistema para a sentença anterior e a anuncia. (suportado apenas no Microsoft Word e Outlook)</td>
        </tr>
    </tbody>
</table>

<p>
    Quando estiver numa tabela, as seguintes teclas de atalho também estarão disponíveis:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Mover para a coluna anterior</td>
            <td>control+alt+seta a esquerda</td>
            <td>Move o cursor do sistema para a coluna anterior (permanecendo na mesma linha)</td>
        </tr>
        <tr>
            <td>Mover para a próxima coluna</td>
            <td>control+alt+seta a direita</td>
            <td>Move o cursor do sistema para a próxima coluna (permanecendo na mesma linha)</td>
        </tr>
        <tr>
            <td>Mover para a linha anterior</td>
            <td>control+alt+seta acima</td>
            <td>Move o cursor do sistema para a linha anterior (permanecendo na mesma coluna)</td>
        </tr>
        <tr>
            <td>Mover para a próxima linha</td>
            <td>control+alt+seta abaixo</td>
            <td>Move o cursor do sistema para a linha seguinte (permanecendo na mesma coluna)</td>
        </tr>
    </tbody>
</table>

<h3>Navegação de Objetos</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Toque [Gesto]</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Anunciar o objeto atual</td>
            <td>NVDA+5 do teclado numérico</td>
            <td>NVDA+shift+o</td>
            <td>nenhum</td>
            <td>Anuncia o objeto de navegação atual. Se pressionada duas vezes, soletra o objeto e, pressionando 3 vezes, copia
                o nome e o valor desse objeto para a área de transferência.</td>
        </tr>
        <tr>
            <td>Mover para o pai do objeto atual</td>
            <td>NVDA+8 do teclado Numérico</td>
            <td>NVDA+shift+seta acima</td>
            <td>Varredura para Cima (Modo de objeto)</td>
            <td>Move para o objeto que contém o atual objeto de navegação</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>NVDA+4 do teclado numérico</td>
            <td>NVDA+shift+seta a esquerda</td>
            <td>Varredura para a esquerda (Modo de objeto)</td>
            <td>Move para o objeto anterior ao objeto de navegação atual</td>
        </tr>
        <tr>
            <td>Mover para o objeto seguinte</td>
            <td>NVDA+6 do teclado numérico</td>
            <td>NVDA+shift+seta a direita</td>
            <td>Varredura para a direita (Modo de objeto)</td>
            <td>Move para o objeto seguinte ao objeto de navegação atual</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>NVDA+2 do teclado numérico</td>
            <td>NVDA+shift+seta abaixo</td>
            <td>Varredura para baixo (Modo de objeto)</td>
            <td>Move para o primeiro objeto contido no objeto de navegação atual</td>
        </tr>
        <tr>
            <td>Mover para o objeto em foco</td>
            <td>NVDA+Menos do teclado numérico</td>
            <td>NVDA+backspace</td>
            <td>nenhum</td>
            <td>Move para o objeto que tem o foco do sistema atual, e também posiciona o cursor de exploração na posição do cursor
                do sistema, se o mesmo estiver visível</td>
        </tr>
        <tr>
            <td>Ativar objeto de navegação atual</td>
            <td>NVDA+Enter do teclado numérico</td>
            <td>NVDA+enter</td>
            <td>Duplo Toque</td>
            <td>Ativa o objeto de navegação atual (o mesmo que clicar com o mouse ou pressionar a barra de espaços quando se
                tem o foco)</td>
        </tr>
        <tr>
            <td>Mover o foco ou o cursor do sistema para a posição atual da exploração</td>
            <td>NVDA+shift+Menos do teclado numérico</td>
            <td>NVDA+shift+backspace</td>
            <td>nenhum</td>
            <td>Se pressionada uma vez, coloca o foco sobre o objeto de navegação atual. Duas vezes, coloca o cursor do sistema
                na posição do cursor de exploração</td>
        </tr>
        <tr>
            <td>Anunciar a localização do cursor de exploração</td>
            <td>NVDA+del do bloco numérico</td>
            <td>NVDA+del</td>
            <td>nenhum</td>
            <td>Anuncia informações sobre a localização do texto ou objeto sob o cursor de exploração. Por exemplo, isso pode
                incluir a percentagem do documento, a distância da borda da página ou a exata posição na tela. Pressionando
                duas vezes, poderá fornecer detalhes adicionais.</td>
        </tr>
    </tbody>
</table>

<h3>Revendo [Explorando] Texto</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Toque [Gesto]</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Mover para a primeira linha em exploração</td>
            <td>shift+7 do teclado numérico</td>
            <td>NVDA+control+home</td>
            <td>nenhum</td>
            <td>Move o cursor de exploração para a primeira linha do texto</td>
        </tr>
        <tr>
            <td>Mover para a linha anterior em exploração</td>
            <td>7 do teclado numérico</td>
            <td>NVDA+seta acima</td>
            <td>Varredura para cima (Modo de texto)</td>
            <td>Move o cursor de exploração para a linha anterior do texto</td>
        </tr>
        <tr>
            <td>Ler linha atual em exploração</td>
            <td>8 do teclado numérico</td>
            <td>NVDA+shift+ponto</td>
            <td>nenhum</td>
            <td>Lê a linha atual do texto onde está posicionado o cursor de exploração. Ao pressionar duas vezes rapidamente
                soletra a linha. Pressionando-se três vezes, soletra-a usando descrições de caracteres.</td>
        </tr>
        <tr>
            <td>Mover para a próxima linha em exploração</td>
            <td>9 do teclado numérico</td>
            <td>NVDA+seta abaixo</td>
            <td>Varredura para baixo (Modo de texto)</td>
            <td>Move o cursor de exploração para a próxima linha do texto</td>
        </tr>
        <tr>
            <td>Mover para a última linha em exploração</td>
            <td>shift+9 do teclado numérico</td>
            <td>NVDA+control+end</td>
            <td>nenhum</td>
            <td>Move o cursor de exploração para a última linha do texto</td>
        </tr>
        <tr>
            <td>Mover para a palavra anterior em exploração</td>
            <td>4 do teclado numérico</td>
            <td>NVDA+control+seta a esquerda</td>
            <td>Varredura para a esquerda com 2 dedos (Modo de texto)</td>
            <td>Move o cursor de exploração para a palavra anterior no texto</td>
        </tr>
        <tr>
            <td>Ler palavra atual em exploração</td>
            <td>5 do teclado numérico</td>
            <td>NVDA+control+ponto</td>
            <td>nenhum</td>
            <td>Anuncia a palavra atual no texto onde está posicionado o cursor de exploração. Ao pressionar duas vezes rapidamente
                soletra a palavra. Três vezes, soletra usando descrições de caracteres.</td>
        </tr>
        <tr>
            <td>Mover para a próxima palavra em exploração</td>
            <td>6 do teclado numérico</td>
            <td>NVDA+control+seta a direita</td>
            <td>Varredura para a direita com 2 dedos (Modo de texto)</td>
            <td>Move o cursor de exploração para a próxima palavra no texto</td>
        </tr>
        <tr>
            <td>mover para o início da linha em exploração</td>
            <td>shift+1 do teclado numérico</td>
            <td>NVDA+home</td>
            <td>nenhum</td>
            <td>Move o cursor de exploração para o primeiro caractere da linha atual no texto</td>
        </tr>
        <tr>
            <td>Mover para o caractere anterior em exploração</td>
            <td>1 do teclado numérico</td>
            <td>NVDA+seta a esquerda</td>
            <td>Varredura para a esquerda (Modo de texto)</td>
            <td>Move o cursor de exploração para o caractere anterior na linha atual no texto</td>
        </tr>
        <tr>
            <td>Ler o caractere atual em exploração</td>
            <td>2 do teclado numérico</td>
            <td>NVDA+ponto</td>
            <td>nenhum</td>
            <td>Anuncia o caractere do objeto de navegação atual onde se encontra o cursor de exploração. Ao pressionar duas
                vezes rapidamente, fornece uma descrição ou exemplo do caractere. Pressionado três vezes, anuncia o valor
                numérico decimal e hexadecimal do caractere.</td>
        </tr>
        <tr>
            <td>Mover para o próximo caractere em exploração</td>
            <td>3 do teclado numérico</td>
            <td>NVDA+seta a direita</td>
            <td>Varredura para a direita (Modo de texto)</td>
            <td>Move o cursor de exploração para o caractere seguinte na linha atual do texto</td>
        </tr>
        <tr>
            <td>Mover para o fim da linha em exploração</td>
            <td>shift+3 do teclado numérico</td>
            <td>NVDA+end</td>
            <td>nenhum</td>
            <td>Move o cursor de exploração para o último caractere da linha atual do texto</td>
        </tr>
        <tr>
            <td>Ler tudo com exploração</td>
            <td>Mais do teclado numérico</td>
            <td>NVDA+shift+a</td>
            <td>Varredura para baixo com 3 dedos (Modo de texto)</td>
            <td>Lê a partir da posição atual do cursor de exploração, movendo-o à medida que avança</td>
        </tr>
        <tr>
            <td>Selecionar e Copiar a partir do cursor de exploração</td>
            <td>NVDA+f9</td>
            <td>NVDA+f9</td>
            <td>nenhum</td>
            <td>Inicia o processo de seleção e cópia do texto a partir da posição atual do cursor de exploração. A ação real
                não é executada até que você informe ao NVDA onde o fim do intervalo de texto está</td>
        </tr>
        <tr>
            <td>Selecionar e Copiar até o cursor de exploração</td>
            <td>NVDA+f10</td>
            <td>NVDA+f10</td>
            <td>nenhum</td>
            <td>Na primeira vez que pressionar, o texto é selecionado a partir do marcador de início de posição previamente definido
                até e incluindo a posição atual do cursor de exploração. Depois de pressionar esta tecla uma segunda vez,
                o texto será copiado para a área de transferência do Windows</td>
        </tr>
        <tr>
            <td>Informar formatação de texto</td>
            <td>NVDA+f</td>
            <td>NVDA+f</td>
            <td>nenhum</td>
            <td>Anuncia a formatação do texto onde o cursor de exploração está posicionado atualmente. Pressionando duas vezes,
                exibe a informação em modo de navegação</td>
        </tr>
    </tbody>
</table>

<h3>Modos de Exploração</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Toque [Gesto]</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Alternar para o modo de exploração seguinte</td>
            <td>NVDA+7 do Teclado numérico</td>
            <td>NVDA+pageUp</td>
            <td>Varredura para cima com 2 dedos</td>
            <td>Alterna para o próximo modo de exploração disponível</td>
        </tr>
        <tr>
            <td>Alternar para o modo de exploração anterior</td>
            <td>NVDA+1 do teclado numérico</td>
            <td>NVDA+pageDown</td>
            <td>Varredura para baixo com 2 dedos</td>
            <td>Alterna para o modo de exploração disponível anterior</td>
        </tr>
    </tbody>
</table>

<h3>Navegando com o Mouse</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Clicar com o botão esquerdo do mouse</td>
            <td>Barra do teclado numérico</td>
            <td>NVDA+abre colchete</td>
            <td>Clica uma vez com o botão esquerdo do mouse. O duplo clique habitual pode ser realizado pressionando duas vezes
                rapidamente este comando</td>
        </tr>
        <tr>
            <td>Prender o botão esquerdo do mouse</td>
            <td>shift+barra do teclado numérico</td>
            <td>NVDA+control+abre colchete</td>
            <td>Mantém o botão esquerdo do mouse pressionado. Execute-o novamente para liberá-lo. Para arrastar o mouse, pressione
                esta tecla de atalho para prender o botão esquerdo e em seguida mova o mouse quer seja fisicamente ou utilizando
                qualquer comando que o movimente</td>
        </tr>
        <tr>
            <td>Clicar com o botão direito do mouse</td>
            <td>Asterisco do teclado numérico</td>
            <td>NVDA+fecha colchete</td>
            <td>Clica uma vez com o botão direito do mouse</td>
        </tr>
        <tr>
            <td>Prender o botão direito do mouse</td>
            <td>shift+asterisco do teclado numérico</td>
            <td>NVDA+control+fecha colchete</td>
            <td>Mantém o botão direito do mouse pressionado. Execute-o novamente para liberá-lo. Para arrastar o mouse, pressione
                esta tecla de atalho para prender o botão direito e em seguida mova-o quer seja fisicamente ou utilizando
                qualquer comando que movimente o mesmo</td>
        </tr>
        <tr>
            <td>Mover o mouse para o objeto de navegação atual</td>
            <td>NVDA+barra do teclado numérico</td>
            <td>NVDA+shift+m</td>
            <td>Move o mouse para a localização do objeto de navegação atual e do cursor de exploração</td>
        </tr>
        <tr>
            <td>Navegar para o objeto sob o mouse</td>
            <td>NVDA+asterisco do teclado numérico</td>
            <td>NVDA+shift+n</td>
            <td>Coloca como objeto de navegação aquele que se encontra sob o ponteiro do mouse</td>
        </tr>
    </tbody>
</table>

<h2>Modo de Navegação</h2>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Alternar entre modos de navegação/foco</td>
            <td>NVDA+espaço</td>
            <td>Alterna entre o modo de foco e o modo de navegação</td>
        </tr>
        <tr>
            <td>Sair do modo de foco</td>
            <td>escape</td>
            <td>Volta para o modo de navegação se o modo de foco foi anteriormente ativado automaticamente</td>
        </tr>
        <tr>
            <td>Atualizar Documento do Modo de Navegação</td>
            <td>NVDA+f5</td>
            <td>Recarrega o conteúdo do documento atual (muito útil se determinado conteúdo parece estar ausente do documento.
                Não disponível no Microsoft Word e Outlook.)</td>
        </tr>
        <tr>
            <td>Procurar</td>
            <td>NVDA+control+f</td>
            <td>Abre um diálogo onde você pode digitar algum texto para procurar no documento atual</td>
        </tr>
        <tr>
            <td>Procurar seguinte</td>
            <td>NVDA+f3</td>
            <td>Procura pela próxima ocorrência de texto já procurada no documento</td>
        </tr>
        <tr>
            <td>Procurar anterior</td>
            <td>NVDA+shift+f3</td>
            <td>Procura pela ocorrência de texto anterior já procurada no documento</td>
        </tr>
        <tr>
            <td>Abrir descrição longa</td>
            <td>NVDA+d</td>
            <td>Abre uma nova janela contendo a descrição longa para o elemento sobre o qual você se encontra caso ele possua
                alguma.
            </td>
        </tr>
    </tbody>
</table>

<h3>Navegação com Caractere Avulso [Navegação Rápida]</h3>
<p>
    As teclas seguintes só por si saltam para o próximo elemento disponível, adicionando-se a tecla Shift faz com que saltem
    para o elemento anterior:
</p>
<ul>
    <li>h: cabeçalho [título]
    </li>
    <li>l: lista
    </li>
    <li>i: item de lista
    </li>
    <li>t: tabela
    </li>
    <li>k: link
    </li>
    <li>n: texto que não é link
    </li>
    <li>f: campo de formulário
    </li>
    <li>u: link não visitado
    </li>
    <li>v: link visitado
    </li>
    <li>e: campo de edição
    </li>
    <li>b: botão
    </li>
    <li>x: caixa de seleção
    </li>
    <li>c: caixa de combinação
    </li>
    <li>r: botão de opção
    </li>
    <li>q: bloco de citação
    </li>
    <li>s: separador
    </li>
    <li>m: frame [quadro]
    </li>
    <li>g: gráfico
    </li>
    <li>d: marca [marco]
    </li>
    <li>o: objeto embutido (tocador de áudio e vídeo, aplicativo, diálogo, etc.)
    </li>
    <li>1 a 6: cabeçalhos [títulos] de nível 1 a 6 respectivamente
    </li>
    <li>a: anotação (comentário, revisão do editor, etc.)
    </li>
    <li>w: erro ortográfico
    </li>
</ul>

<p>
    Para mover-se ao início ou final de elementos que contém outros, tais como listas e tabelas:
</p>
<table width="100%">
    <tbody>
        <tr>
            <td>Nome</td>
            <td>Tecla</td>
            <td>Descrição</td>
        </tr>
        <tr>
            <td>Mover para o início do contêiner</td>
            <td>shift+vírgula</td>
            <td>Move para o início do elemento que contém outros (lista, tabela etc.) onde o cursor esteja posicionado</td>
        </tr>
        <tr>
            <td>Mover para depois do final do contêiner</td>
            <td>vírgula</td>
            <td>Passa para depois do final do elemento que contém outros (lista, tabela, etc.) onde esteja situado o cursor</td>
        </tr>
    </tbody>
</table>

<p>
    Para alternar a ativação das teclas de navegação com caracteres avulsos no documento atual, pressione NVDA+shift+espaço.
</p>
<h3>A Lista de Elementos</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Lista de elementos do Modo de Navegação</td>
            <td>NVDA+f7</td>
            <td>Lista vários tipos de elementos no documento atual</td>
        </tr>
    </tbody>
</table>

<h3>Objetos Embutidos</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Mover para o Documento que contém o objeto embutido</td>
            <td>NVDA+control+espaço</td>
            <td>Move o foco para fora do objeto embutido atual e retorna ao Documento que o contém</td>
        </tr>
    </tbody>
</table>

<h2>Lendo Conteúdo Matemático</h2>
<h3>Navegação Interativa</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Interagir com conteúdo matemático</td>
            <td>NVDA+alt+m</td>
            <td>Inicia a interação com o conteúdo matemático.</td>
        </tr>
    </tbody>
</table>

<h2>Braille</h2>
<h3>Entrada [digitação] em Braille</h3>
<p>
    Pressionar o ponto 7 apaga a última célula ou caractere braille inserido. Ponto 8 transcreve qualquer entrada braille e pressiona
    a tecla enter. Pressionar o ponto 7 + ponto 8 transcreve qualquer entrada em braille, mas sem adicionar um espaço ou
    pressionar enter.
</p>
<h2>Reconhecimento de Conteúdo</h2>
<h3>OCR do Windows 10</h3>
<p>
    Para reconhecer o texto no objeto de navegação atual usando o OCR do Windows 10, pressione NVDA+r.
</p>
<h2>Recursos do NVDA para Aplicações Específicas</h2>
<h3>Microsoft Word</h3>
<h4>Leitura Automática dos Cabeçalhos das Linhas e Colunas</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Definir os cabeçalhos das colunas</td>
            <td>NVDA+shift+c</td>
            <td>Pressionado uma vez, informa ao NVDA que esta é a linha que contém os cabeçalhos das colunas, os quais deverão
                ser anunciados automaticamente ao mover-se entre colunas abaixo dessa linha. Ao pressionar duas vezes, limpará
                a configuração.</td>
        </tr>
        <tr>
            <td>Definir os cabeçalhos das linhas</td>
            <td>NVDA+shift+r</td>
            <td>Pressionando-se uma vez, informa ao NVDA que esta é a coluna que contém os cabeçalhos das linhas, os quais deverão
                ser anunciados automaticamente ao mover-se entre linhas dentro desta coluna. Pressione duas vezes e limpará
                a configuração.</td>
        </tr>
    </tbody>
</table>


<h4>Modo de Navegação no Microsoft Word</h4>
<p>
    Para alternar a ativação do Modo de navegação no Microsoft Word, pressione NVDA+espaço.
</p>

<h5>A Lista de Elementos</h5>
<p>
    Estando em modo de navegação no Microsoft Word, você pode acessar a Lista de Elementos pressionando NVDA+f7.
</p>

<h4>Anunciar Comentários</h4>
<p>
    Para anunciar quaisquer comentários na posição atual do cursor do sistema, pressione NVDA+alt+c.
</p>
<h3>Microsoft Excel</h3>
<h4>Leitura Automática dos Cabeçalhos das Linhas e Colunas</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Definir os cabeçalhos das colunas</td>
            <td>NVDA+shift+c</td>
            <td>Pressionado uma vez, informa ao NVDA que esta é a linha que contém os cabeçalhos das colunas, os quais deverão
                ser anunciados automaticamente ao mover-se entre colunas abaixo dessa linha. Ao pressionar duas vezes, limpará
                a configuração.</td>
        </tr>
        <tr>
            <td>Definir os cabeçalhos das linhas</td>
            <td>NVDA+shift+r</td>
            <td>Pressionando-se uma vez, informa ao NVDA que esta é a coluna que contém os cabeçalhos das linhas, os quais deverão
                ser anunciados automaticamente ao mover-se entre linhas dentro desta coluna. Pressione duas vezes e limpará
                a configuração.</td>
        </tr>
    </tbody>
</table>
<h4>A Lista de Elementos</h4>
<p>
    Para acessar a Lista de Elementos no Microsoft Excel, pressione NVDA+f7.
</p>
<h4>Anunciar Comentários</h4>
<p>
    Para anunciar quaisquer comentários na célula atualmente sob o foco, pressione NVDA+alt+c.
</p>
<h4>Lendo Células Protegidas</h4>
<p>
    Para ser possível mover-se para células bloqueadas, alterne para o Modo de Navegação pressionando NVDA+espaço, em seguida
    use os comandos de movimento padrões do Excel, tais como as setas, para mover-se por todas as células da planilha.
</p>
<h3>Microsoft PowerPoint</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Alternar leitura de notas e slides</td>
            <td>control+shift+s</td>
            <td>Estando num slide em execução, esse comando alternará entre as notas para o slide e o conteúdo do mesmo. Isso
                afeta somente o que o NVDA lê, não o que será mostrado na tela.</td>
        </tr>
    </tbody>
</table>

<h3>foobar2000</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Anunciar o tempo restante</td>
            <td>control+shift+r</td>
            <td>Anuncia o tempo restante para a faixa atualmente em execução, caso haja alguma.</td>
        </tr>
    </tbody>
</table>

<h3>Miranda IM</h3>
<table width="100%">
    <tbody>
        <tr>
            <td>Nome</td>
            <td>Tecla</td>
            <td>Descrição</td>
        </tr>
        <tr>
            <td>Anunciar mensagem recente</td>
            <td>NVDA+control+1-4</td>
            <td>Anuncia uma das mensagens mais recentes, dependendo do número pressionado; isto é, NVDA+control+2 lê a segunda
                mensagem mais recente.</td>
        </tr>
    </tbody>
</table>

<h3>Poedit</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Anunciar Janela de Comentários</td>
            <td>control+shift+c</td>
            <td>Anuncia qualquer comentário na janela de comentários.</td>
        </tr>
        <tr>
            <td>Anunciar notas para tradutores</td>
            <td>control+shift+a</td>
            <td>Anuncia quaisquer notas para tradutores.</td>
        </tr>
    </tbody>
</table>

<h3>Skype</h3>
<p>
    Quando em uma conversa:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Rever mensagem</td>
            <td>NVDA+control+1-0</td>
            <td>Anuncia e move o cursor de exploração para uma mensagem recente, dependendo do número pressionado, isto é, NVDA+control+2
                lê a segunda mensagem mais recente.</td>
        </tr>
    </tbody>
</table>

<h3>Kindle para PC</h3>
<p>
    É possível virar manualmente para a próxima página com a tecla pageDown e para a página anterior com a tecla pageUp.
</p>
<h4>Seleção de Texto</h4>
<p>
    Uma vez selecionado o texto, pressione a tecla aplicação ou shift+f10 para exibir as opções disponíveis para trabalhar com
    a seleção.
</p>
<h3>Azardi</h3>
<p>
    Quando na visualização da tabela de livros adicionados:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Enter</td>
            <td>enter</td>
            <td>Abre o livro selecionado.</td>
        </tr>
        <tr>
            <td>Menu de contexto</td>
            <td>aplicações</td>
            <td>Abre o menu de contexto para o livro selecionado.</td>
        </tr>
    </tbody>
</table>

<h2>Configurando o NVDA</h2>
<h3>Opções do NVDA</h3>
<h4>Configurações de Fala (NVDA+control+v)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Grau de Pontuação/Sinais</td>
            <td>NVDA+p</td>
            <td>NVDA+p</td>
            <td>Essa opção permite-lhe escolher a quantidade de pontuação e outros sinais [símbolos] que devem ser falados como
                palavras.
            </td>
        </tr>
    </tbody>
</table>

<h4>Selecionar Sintetizador (NVDA+control+s)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Modo de Áudio Prioritário [Ducking]</td>
            <td>NVDA+shift+d</td>
            <td>NVDA+shift+d</td>
            <td>No Windows 8 e superiores, essa opção permite-lhe escolher se o NVDA deve reduzir o volume de outros aplicativos
                enquanto ele estiver falando, ou durante todo o tempo em que o NVDA estiver em execução.</td>
        </tr>
    </tbody>
</table>

<h4>O Anel de Configurações de Voz</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Mover para a próxima opção de voz</td>
            <td>NVDA+control+seta a direita</td>
            <td>NVDA+shift+control+seta a direita</td>
            <td>Move para a próxima opção de voz disponível depois da atual e circula novamente para a primeira opção depois
                da última</td>
        </tr>
        <tr>
            <td>Mover para a opção de voz anterior</td>
            <td>NVDA+control+seta a esquerda</td>
            <td>NVDA+shift+control+seta a esquerda</td>
            <td>Move para a opção de voz anterior disponível depois da atual e circula novamente para a última depois da primeira
            </td>
        </tr>
        <tr>
            <td>Aumentar a opção de voz atual</td>
            <td>NVDA+control+seta acima</td>
            <td>NVDA+shift+control+seta acima</td>
            <td>aumenta a opção de voz atual onde estiver. Ex: aumenta a velocidade, escolhe a voz seguinte, aumenta o volume</td>
        </tr>
        <tr>
            <td>Diminuir a opção de voz atual</td>
            <td>NVDA+control+seta abaixo</td>
            <td>NVDA+shift+control+seta abaixo</td>
            <td>Diminui a opção de voz atual onde estiver. Ex: diminui a velocidade, escolhe a voz anterior, diminui o volume</td>
        </tr>
    </tbody>
</table>

<h4>Braille</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Vincular Braille</td>
            <td>NVDA+control+t</td>
            <td>NVDA+control+t</td>
            <td>Esta opção permite-lhe escolher se a linha Braille seguirá o cursor do sistema, o navegador de objetos / cursor
                de exploração, ou ambos.</td>
        </tr>
    </tbody>
</table>

<h4>Teclado (NVDA+control+k)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Falar Caracteres Digitados</td>
            <td>NVDA+2</td>
            <td>NVDA+2</td>
            <td>Consiste numa caixa de seleção que quando marcada informa ao NVDA para anunciar todos os caracteres introduzidos
                através do teclado.</td>
        </tr>
        <tr>
            <td align="center">Falar Palavras Digitadas</td>
            <td>NVDA+3</td>
            <td>NVDA+3</td>
            <td>Quando está selecionada faz com que o NVDA anuncie todas as palavras que você introduzir através do teclado.</td>
        </tr>
        <tr>
            <td align="center">Falar Teclas de Comando</td>
            <td>NVDA+4</td>
            <td>NVDA+4</td>
            <td>Quando está marcada, informa ao NVDA para anunciar todas as teclas que não são caracteres que você pressionar
                através do teclado. Isto inclui combinações de teclas tais como o Control mais outra letra.</td>
        </tr>
    </tbody>
</table>

<h4>Mouse (NVDA+control+m)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Habilitar Rastreamento do Mouse</td>
            <td>NVDA+m</td>
            <td>NVDA+m</td>
            <td>Esta é uma caixa de seleção que quando marcada faz com que o NVDA anuncie o texto atual sobre o ponteiro do mouse,
                conforme este se move pela tela.</td>
        </tr>
    </tbody>
</table>

<h4>Cursor de Exploração</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Acompanhar Foco do Teclado</td>
            <td>NVDA+7</td>
            <td>NVDA+7</td>
            <td>Quando ativado, o cursor de exploração será sempre colocado no mesmo objeto quando o foco atual for alterado.</td>
        </tr>
        <tr>
            <td align="center">Acompanhar Cursor do Sistema</td>
            <td>NVDA+6</td>
            <td>NVDA+6</td>
            <td>Quando ativada, o cursor de exploração será movido automaticamente para a posição do cursor do sistema a cada
                vez que se mover.</td>
        </tr>
    </tbody>
</table>

<h4>Apresentação de Objetos (NVDA+control+o)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Informação da barra de progresso</td>
            <td>NVDA+u</td>
            <td>NVDA+u</td>
            <td>Esta opção controla como o NVDA informará as atualizações nas barras de progresso.</td>
        </tr>
        <tr>
            <td align="center">Anunciar atualizações nos conteúdos dinâmicos</td>
            <td>NVDA+5</td>
            <td>NVDA+5</td>
            <td>Alterna o anúncio de novos conteúdos em objetos particulares tais como terminais e o controle de históricos em
                programas de conversação.</td>
        </tr>
    </tbody>
</table>

<h4>Modo de Navegação (NVDA+control+b)</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td align="center">Usar Apresentação da Tela</td>
            <td>NVDA+v</td>
            <td>NVDA+v</td>
            <td>Esta opção permite definir se o conteúdo no modo de navegação deve posicionar os elementos como links e outros
                campos numa linha individual, ou se se deve conservá-los dentro do texto tal como aparece na tela. Se a opção
                estiver marcada, os elementos ficarão como aparecem visualmente. Mas se estiver desmarcada, os campos serão
                colocados numa linha separadamente.</td>
        </tr>
    </tbody>
</table>

<h3>Salvando e Restaurando Configurações</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla de Desktop</th>
            <th>Tecla de Laptop</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>Salvar Configuração</td>
            <td>NVDA+control+c</td>
            <td>NVDA+control+c</td>
            <td>Salva sua configuração atual, de modo que não se perca quando sair do NVDA</td>
        </tr>
        <tr>
            <td>Voltar à Configuração Salva</td>
            <td>NVDA+control+r</td>
            <td>NVDA+control+r</td>
            <td>Pressionada uma vez retorna suas configurações para aquelas salvas da última vez. Pressionando-se 3 vezes irá
                retorná-las aos padrões originais.</td>
        </tr>
    </tbody>
</table>

<h3>Perfis de Configuração</h3>
<h4>Gerenciamento Básico</h4>
<ul>
    <li>NVDA+control+p: Exibe o Diálogo de Perfis de Configuração.
    </li>
</ul>

<p></p>
<h2>Linhas Braille Suportadas</h2>
<h3>Freedom Scientific Focus/PAC Mate Series</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>topRouting1 (primeira célula da linha)</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>topRouting20/40/80 (última célula da linha)</td>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>leftAdvanceBar</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>rightAdvanceBar</td>
        </tr>
        <tr>
            <td>Alternar "vínculo do Braille"</td>
            <td>leftGDFButton+rightGDFButton</td>
        </tr>
        <tr>
            <td>Alternar ação da roda esquerda</td>
            <td>pressionar a roda esquerda</td>
        </tr>
        <tr>
            <td>Mover-se para trás usando a ação da roda esquerda</td>
            <td>roda esquerda para cima</td>
        </tr>
        <tr>
            <td>Mover-se para a frente usando a ação da roda esquerda</td>
            <td>roda esquerda para baixo</td>
        </tr>
        <tr>
            <td>Alternar ação da roda direita</td>
            <td>pressionar a roda direita</td>
        </tr>
        <tr>
            <td>Mover-se para Trás usando a ação da roda direita</td>
            <td>roda direita para cima</td>
        </tr>
        <tr>
            <td>Mover-se para a frente usando a ação da roda Direita</td>
            <td>roda direita para baixo</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Tecla backspace</td>
            <td>ponto 7</td>
        </tr>
        <tr>
            <td>Tecla enter</td>
            <td>ponto 8</td>
        </tr>
        <tr>
            <td>Comando shift+tab</td>
            <td>brailleSpaceBar+ponto 1+ponto 2</td>
        </tr>
        <tr>
            <td>Tecla tab</td>
            <td>brailleSpaceBar+ponto 4+ponto 5</td>
        </tr>
        <tr>
            <td>Tecla seta cima</td>
            <td>brailleSpaceBar+ponto 1</td>
        </tr>
        <tr>
            <td>Tecla seta baixo</td>
            <td>brailleSpaceBar+ponto 4</td>
        </tr>
        <tr>
            <td>Tecla control+seta a esquerda</td>
            <td>brailleSpaceBar+ponto 2</td>
        </tr>
        <tr>
            <td>Tecla control+seta direita</td>
            <td>brailleSpaceBar+ponto 5</td>
        </tr>
        <tr>
            <td>Tecla seta esquerda</td>
            <td>brailleSpaceBar+ponto 3</td>
        </tr>
        <tr>
            <td>Tecla seta direita</td>
            <td>brailleSpaceBar+ponto 6</td>
        </tr>
        <tr>
            <td>Tecla home</td>
            <td>brailleSpaceBar+ponto 1+ponto 3</td>
        </tr>
        <tr>
            <td>tecla end</td>
            <td>brailleSpaceBar+ponto 4+ponto 6</td>
        </tr>
        <tr>
            <td>Tecla control+home</td>
            <td>brailleSpaceBar+ponto 1+ponto 2ponto3</td>
        </tr>
        <tr>
            <td>Tecla control+end</td>
            <td>brailleSpaceBar+ponto 4+ponto 5+ponto 6</td>
        </tr>
        <tr>
            <td>Tecla alt</td>
            <td>brailleSpaceBar+ponto 1+ponto 3+ponto 4</td>
        </tr>
        <tr>
            <td>Tecla alt+tab</td>
            <td>brailleSpaceBar+ponto 2+ponto 3+ponto 4+ponto 5</td>
        </tr>
        <tr>
            <td>Tecla escape</td>
            <td>brailleSpaceBar+ponto 1+ponto 5</td>
        </tr>
        <tr>
            <td>Tecla windows</td>
            <td>brailleSpaceBar+ponto 2+ponto 4+ponto 5+ponto 6</td>
        </tr>
        <tr>
            <td>Tecla espaço</td>
            <td>brailleSpaceBar</td>
        </tr>
        <tr>
            <td>Tecla windows+d (minimizar todas as aplicações)</td>
            <td>brailleSpaceBar+ponto 1+ponto 2+ponto 3+ponto 4+ponto 5+ponto 6</td>
        </tr>
        <tr>
            <td>Anunciar a linha atual</td>
            <td>brailleSpaceBar+ponto 1+ponto 4</td>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>brailleSpaceBar+ponto 1ponto 3+ponto 4+ponto 5</td>
        </tr>
    </tbody>
</table>

<p>
    Para modelos mais recentes da Focus que possuam teclas "rocker bar" (focus 40, focus 80 e focus blue):
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>leftRockerBarUp, rightRockerBarUp</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>leftRockerBarDown, rightRockerBarDown</td>
        </tr>
    </tbody>
</table>

<p>
    Apenas para a Focus 80:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>leftBumperBarUp, rightBumperBarUp</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>leftBumperBarDown, rightBumperBarDown</td>
        </tr>
    </tbody>
</table>

<h3>Optelec ALVA séries 6 / conversor de protocolo</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>t1 ou etouch1</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>t2</td>
        </tr>
        <tr>
            <td>Mover para o foco atual</td>
            <td>t3</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>t4</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>t5 ou etouch3</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em célula braille</td>
            <td>sensor secundário</td>
        </tr>
        <tr>
            <td>Alternar a simulação de teclado HID</td>
            <td>t1+spEnter</td>
        </tr>
        <tr>
            <td>Mover para a primeira linha em exploração</td>
            <td>t1+t2</td>
        </tr>
        <tr>
            <td>Mover para a última linha em exploração</td>
            <td>t4+t5</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>t1+t3</td>
        </tr>
        <tr>
            <td>Anunciar título</td>
            <td>etouch2</td>
        </tr>
        <tr>
            <td>Ler a barra de status</td>
            <td>etouch4</td>
        </tr>
        <tr>
            <td>tecla shift+tab</td>
            <td>sp1</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>sp2</td>
        </tr>
        <tr>
            <td>tecla escape</td>
            <td>sp3</td>
        </tr>
        <tr>
            <td>tecla tab</td>
            <td>sp4</td>
        </tr>
        <tr>
            <td>tecla seta acima</td>
            <td>spUp</td>
        </tr>
        <tr>
            <td>tecla seta abaixo</td>
            <td>spDown</td>
        </tr>
        <tr>
            <td>tecla seta a esquerda</td>
            <td>spLeft</td>
        </tr>
        <tr>
            <td>tecla seta a direita</td>
            <td>spRight</td>
        </tr>
        <tr>
            <td>tecla enter</td>
            <td>spEnter, enter</td>
        </tr>
        <tr>
            <td>Anunciar data/hora</td>
            <td>sp1+sp2</td>
        </tr>
        <tr>
            <td>menu do NVDA</td>
            <td>sp1+sp3</td>
        </tr>
        <tr>
            <td>tecla windows+d (minimizar todas as aplicações)</td>
            <td>sp1+sp4</td>
        </tr>
        <tr>
            <td>tecla windows+b (colocar a área de notificação em foco)</td>
            <td>sp3+sp4</td>
        </tr>
        <tr>
            <td>tecla windows</td>
            <td>sp2+sp3, windows</td>
        </tr>
        <tr>
            <td>tecla alt+tab</td>
            <td>sp2+sp4</td>
        </tr>
        <tr>
            <td>tecla control+home</td>
            <td>t3+spUp</td>
        </tr>
        <tr>
            <td>tecla control+end</td>
            <td>t3+spDown</td>
        </tr>
        <tr>
            <td>tecla home</td>
            <td>t3+spLeft</td>
        </tr>
        <tr>
            <td>tecla end</td>
            <td>t3+spRight</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>alt</td>
        </tr>
        <tr>
            <td>tecla control</td>
            <td>control</td>
        </tr>
    </tbody>
</table>

<h3>Linhas Handy Tech</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>esquerda, para cima, b3</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>Direita, para baixo, b6</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>b4</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>b5</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>tecla shift+tab</td>
            <td>esc, tecla de ação tripla esquerda para cima + para baixo</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>b2+b4+b5</td>
        </tr>
        <tr>
            <td>tecla escape</td>
            <td>b4+b6</td>
        </tr>
        <tr>
            <td>tecla tab</td>
            <td>enter, tecla de ação tripla direita para cima + para baixo</td>
        </tr>
        <tr>
            <td>tecla enter</td>
            <td>esc+enter, tecla de tripla ação esquerda+direita para cima + para baixo, joystickAction [açãoDeJoystick]</td>
        </tr>
        <tr>
            <td>tecla seta acima</td>
            <td>joystickUp [joystickParaCima]</td>
        </tr>
        <tr>
            <td>tecla seta abaixo</td>
            <td>joystickDown [joystickParaBaixo]</td>
        </tr>
        <tr>
            <td>tecla seta para esquerda</td>
            <td>joystickLeft [joystickParaEsquerda]</td>
        </tr>
        <tr>
            <td>tecla seta para direita</td>
            <td>joystickRight [joystickParaDireita]</td>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>b2+b4+b5+b6</td>
        </tr>
        <tr>
            <td>Alternar braille vinculado a</td>
            <td>b2</td>
        </tr>
        <tr>
            <td>Alternar o cursor braille</td>
            <td>b1</td>
        </tr>
        <tr>
            <td>Alternar apresentação do contexto do foco</td>
            <td>b7</td>
        </tr>
        <tr>
            <td>Alternar entrada de braille [digitação em braille]</td>
            <td>espaço+b1+b3+b4 (espaço+B maiúsculo)</td>
        </tr>
    </tbody>
</table>

<h3>MDV Lilli</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover Linha Braille para a Frente</td>
            <td>LF</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para Trás</td>
            <td>RG</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para Linha Anterior</td>
            <td>UP</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para Linha Seguinte</td>
            <td>DN</td>
        </tr>
        <tr>
            <td>Guiar para a Cela Braille</td>
            <td>Sensor</td>
        </tr>
        <tr>
            <td>Tecla Shift+Tab</td>
            <td>SLF</td>
        </tr>
        <tr>
            <td>Tecla Tab</td>
            <td>SRG</td>
        </tr>
        <tr>
            <td>Tecla Alt+Tab</td>
            <td>SDN</td>
        </tr>
        <tr>
            <td>Tecla Alt+Shift+Tab</td>
            <td>SUP</td>
        </tr>
    </tbody>
</table>

<h3>Linhas Braille Baum/Humanware/APH/Orbit</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>mover linha braille para trás</td>
            <td>d2</td>
        </tr>
        <tr>
            <td>mover linha braille para a frente</td>
            <td>d5</td>
        </tr>
        <tr>
            <td>mover linha braille para a linha anterior</td>
            <td>d1</td>
        </tr>
        <tr>
            <td>mover linha braille para a linha seguinte</td>
            <td>d3</td>
        </tr>
        <tr>
            <td>guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
    </tbody>
</table>

<p>
    Para linhas que tenham joystick:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>tecla seta acima</td>
            <td>cima</td>
        </tr>
        <tr>
            <td>tecla seta abaixo</td>
            <td>baixo</td>
        </tr>
        <tr>
            <td>tecla seta a esquerda</td>
            <td>esquerda</td>
        </tr>
        <tr>
            <td>tecla seta a direita</td>
            <td>direita</td>
        </tr>
        <tr>
            <td>tecla enter</td>
            <td>selecionar</td>
        </tr>
    </tbody>
</table>

<h3>hedo ProfiLine USB</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover Linha Braille para Trás</td>
            <td>K1</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para a Frente</td>
            <td>K3</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para a Linha Anterior</td>
            <td>B2</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>B5</td>
        </tr>
        <tr>
            <td>Guiar para a Cela Braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Alternar Vínculo do Braille</td>
            <td>K2</td>
        </tr>
        <tr>
            <td>Leitura Contínua</td>
            <td>B6</td>
        </tr>
    </tbody>
</table>

<h3>hedo MobilLine USB</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover Linha Braille para Trás</td>
            <td>K1</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para a Frente</td>
            <td>K3</td>
        </tr>
        <tr>
            <td>Mover Linha Braille para a Linha Anterior</td>
            <td>B2</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>B5</td>
        </tr>
        <tr>
            <td>Guiar para a Cela Braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Alternar Vínculo do Braille</td>
            <td>K2</td>
        </tr>
        <tr>
            <td>Leitura Contínua</td>
            <td>B6</td>
        </tr>
    </tbody>
</table>

<h3>HumanWare Brailliant BI/B Series / BrailleNote Touch</h3>
<h4>Atribuições de teclas para todos os modelos</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>esquerda</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>direita</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>cima</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>baixo</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>cima+baixo</td>
        </tr>
        <tr>
            <td>Tecla seta acima</td>
            <td>espaço+ponto1</td>
        </tr>
        <tr>
            <td>Tecla seta abaixo</td>
            <td>espaço+ponto4</td>
        </tr>
        <tr>
            <td>Tecla seta a esquerda</td>
            <td>espaço+ponto3</td>
        </tr>
        <tr>
            <td>Tecla seta a direita</td>
            <td>espaço+ponto6</td>
        </tr>
        <tr>
            <td>Tecla shift+tab</td>
            <td>espaço+ponto1+ponto3</td>
        </tr>
        <tr>
            <td>Tecla tab</td>
            <td>espaço+ponto4+ponto6</td>
        </tr>
        <tr>
            <td>Tecla alt</td>
            <td>espaço+ponto1+ponto3+ponto4 (espaço+m)</td>
        </tr>
        <tr>
            <td>Tecla escape</td>
            <td>espaço+ponto1+ponto5 (espaço+e)</td>
        </tr>
        <tr>
            <td>Tecla enter</td>
            <td>ponto8</td>
        </tr>
        <tr>
            <td>Tecla windows</td>
            <td>espaço+ponto3+ponto4</td>
        </tr>
        <tr>
            <td>Tecla alt+tab</td>
            <td>espaço+ponto2+ponto3+ponto4+ponto5 (espaço+t)</td>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>espaço+ponto1+ponto3+ponto4+ponto5 (espaço+n)</td>
        </tr>
        <tr>
            <td>Tecla windows+d (minimizar todos os aplicativos)</td>
            <td>espaço+ponto1+ponto4+ponto5 (espaço+d)</td>
        </tr>
        <tr>
            <td>Leitura Contínua</td>
            <td>espaço+ponto1+ponto2+ponto3+ponto4+ponto5+ponto6</td>
        </tr>
    </tbody>
</table>

<h4>Atribuições de teclas para Brailliant BI 32, BI 40 e B 80</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>c1+c3+c4+c5 (comando n)</td>
        </tr>
        <tr>
            <td>Tecla windows+d (minimizar todos os aplicativos)</td>
            <td>c1+c4+c5 (comando d)</td>
        </tr>
        <tr>
            <td>Leitura Contínua</td>
            <td>c1+c2+c3+c4+c5+c6</td>
        </tr>
    </tbody>
</table>

<h4>Atribuições de teclas para Brailliant BI 14</h4>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>tecla seta para cima</td>
            <td>joystick para cima</td>
        </tr>
        <tr>
            <td>tecla seta para baixo</td>
            <td>joystick para baixo</td>
        </tr>
        <tr>
            <td>tecla seta para esquerda</td>
            <td>joystick para esquerda</td>
        </tr>
        <tr>
            <td>tecla seta para direita</td>
            <td>joystick para direita</td>
        </tr>
        <tr>
            <td>tecla enter</td>
            <td>joystick action [joystick ação]</td>
        </tr>
    </tbody>
</table>

<h3>HIMS Séries Braille Sense/Braille EDGE/Smart Beetle/Sync Braille</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>deslocadorEsquerdoParaCima, deslocadorDireitoParaCima, deslocadorEsquerdo</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>deslocadorEsquerdoParaBaixo, deslocadorDireitoParaBaixo, deslocadorDireito</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>deslocadorEsquerdoParaCima+deslocadorDireitoParaCima</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>deslocadorEsquerdoParaBaixo+deslocadorDireitoParaBaixo</td>
        </tr>
        <tr>
            <td>Mover para a linha anterior em exploração</td>
            <td>deslocadorDireitoSetaParaCima</td>
        </tr>
        <tr>
            <td>Mover para a próxima linha em exploração</td>
            <td>deslocadorDireitoSetaParaBaixo</td>
        </tr>
        <tr>
            <td>Mover para o caractere anterior em exploração</td>
            <td>deslocadorDireitoSetaParaEsquerda</td>
        </tr>
        <tr>
            <td>Mover para o próximo caractere em exploração</td>
            <td>deslocadorDireitoSetaParaDireita</td>
        </tr>
        <tr>
            <td>Mover para o foco atual</td>
            <td>deslocadorEsquerdoParaCima+deslocadorEsquerdoParaBaixo, deslocadorDireitoParaCima+deslocadorDireitoParaBaixo,
                deslocadorEsquerdo+deslocadorDireito
            </td>
        </tr>
        <tr>
            <td>tecla control</td>
            <td>smartbeetle:f1, brailleedge:f3</td>
        </tr>
        <tr>
            <td>tecla windows</td>
            <td>f7, smartbeetle:f2</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>ponto1+ponto3+ponto4+espaço, f2, smartbeetle:f3, brailleedge:f4</td>
        </tr>
        <tr>
            <td>tecla shift</td>
            <td>f5</td>
        </tr>
        <tr>
            <td>tecla insert</td>
            <td>ponto2+ponto4+espaço, f6</td>
        </tr>
        <tr>
            <td>tecla aplicações</td>
            <td>ponto1+ponto2+ponto3+ponto4+espaço, f8</td>
        </tr>
        <tr>
            <td>tecla capsLock</td>
            <td>ponto1+ponto3+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla tab</td>
            <td>ponto4+ponto5+espaço, f3, brailleedge:f2</td>
        </tr>
        <tr>
            <td>tecla shift+alt+tab</td>
            <td>f2+f3+f1</td>
        </tr>
        <tr>
            <td>tecla alt+tab</td>
            <td>f2+f3</td>
        </tr>
        <tr>
            <td>tecla shift+tab</td>
            <td>ponto1+ponto2+espaço</td>
        </tr>
        <tr>
            <td>tecla end</td>
            <td>ponto4+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla control+end</td>
            <td>ponto4+ponto5+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla home</td>
            <td>ponto1+ponto3+espaço, smartbeetle:f4</td>
        </tr>
        <tr>
            <td>tecla control+home</td>
            <td>ponto1+ponto2+ponto3+espaço</td>
        </tr>
        <tr>
            <td>tecla alt+f4</td>
            <td>ponto1+ponto3+ponto5+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla setaParaEsquerda</td>
            <td>ponto3+espaço, deslocadorEsquerdoSetaParaEsquerda</td>
        </tr>
        <tr>
            <td>tecla control+shift+setaParaEsquerda</td>
            <td>ponto2+ponto8+espaço+f1</td>
        </tr>
        <tr>
            <td>tecla control+setaParaEsquerda</td>
            <td>ponto2+espaço</td>
        </tr>
        <tr>
            <td>tecla shift+alt+setaParaEsquerda</td>
            <td>ponto2+ponto7+f1</td>
        </tr>
        <tr>
            <td>tecla alt+setaParaEsquerda</td>
            <td>ponto2+ponto7</td>
        </tr>
        <tr>
            <td>tecla setaParaDireita</td>
            <td>ponto6+espaço, deslocadorEsquerdoSetaParaDireita</td>
        </tr>
        <tr>
            <td>tecla control+shift+setaParaDireita</td>
            <td>ponto5+ponto8+espaço+f1</td>
        </tr>
        <tr>
            <td>tecla control+setaParaDireita</td>
            <td>ponto5+espaço</td>
        </tr>
        <tr>
            <td>tecla shift+alt+setaParaDireita</td>
            <td>ponto5+ponto7+f1</td>
        </tr>
        <tr>
            <td>tecla alt+setaParaDireita</td>
            <td>ponto5+ponto7</td>
        </tr>
        <tr>
            <td>tecla pageUp</td>
            <td>ponto1+ponto2+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla control+pageUp</td>
            <td>ponto1+ponto2+ponto6+ponto8+espaço</td>
        </tr>
        <tr>
            <td>tecla setaParaCima</td>
            <td>ponto1+espaço, deslocadorEsquerdoSetaParaCima</td>
        </tr>
        <tr>
            <td>tecla control+shift+setaParaCima</td>
            <td>ponto2+ponto3+ponto8+espaço+f1</td>
        </tr>
        <tr>
            <td>tecla control+setaParaCima</td>
            <td>ponto2+ponto3+espaço</td>
        </tr>
        <tr>
            <td>tecla shift+alt+setaParaCima</td>
            <td>ponto2+ponto3+ponto7+f1</td>
        </tr>
        <tr>
            <td>tecla alt+setaParaCima</td>
            <td>ponto2+ponto3+ponto7</td>
        </tr>
        <tr>
            <td>tecla shift+setaParaCima</td>
            <td>deslocadorEsquerdoParaBaixo+espaço</td>
        </tr>
        <tr>
            <td>tecla pageDown</td>
            <td>ponto3+ponto4+ponto5+espaço</td>
        </tr>
        <tr>
            <td>tecla control+pageDown</td>
            <td>ponto3+ponto4+ponto5+ponto8+espaço</td>
        </tr>
        <tr>
            <td>tecla setaParaBaixo</td>
            <td>ponto4+espaço, deslocadorEsquerdoSetaParaBaixo</td>
        </tr>
        <tr>
            <td>tecla control+shift+setaParaBaixo</td>
            <td>ponto5+ponto6+ponto8+espaço+f1</td>
        </tr>
        <tr>
            <td>tecla control+setaParaBaixo</td>
            <td>ponto5+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla shift+alt+setaParaBaixo</td>
            <td>ponto5+ponto6+ponto7+f1</td>
        </tr>
        <tr>
            <td>tecla alt+setaParaBaixo</td>
            <td>ponto5+ponto6+ponto7</td>
        </tr>
        <tr>
            <td>tecla shift+setaParaBaixo</td>
            <td>espaço+deslocadorDireitoParaBaixo</td>
        </tr>
        <tr>
            <td>tecla esc</td>
            <td>ponto1+ponto5+espaço, f4, brailleedge:f1</td>
        </tr>
        <tr>
            <td>tecla delete</td>
            <td>ponto1+ponto3+ponto5+espaço, ponto1+ponto4+ponto5+espaço</td>
        </tr>
        <tr>
            <td>tecla f1</td>
            <td>ponto1+ponto2+ponto5+espaço</td>
        </tr>
        <tr>
            <td>tecla f3</td>
            <td>ponto1+ponto2+ponto4+ponto8</td>
        </tr>
        <tr>
            <td>tecla f4</td>
            <td>ponto7+f3</td>
        </tr>
        <tr>
            <td>tecla windows+b</td>
            <td>ponto1+ponto2+f1</td>
        </tr>
        <tr>
            <td>tecla windows+d</td>
            <td>ponto1+ponto4+ponto5+f1</td>
        </tr>
        <tr>
            <td>tecla control+insert</td>
            <td>smartbeetle:f1+deslocadorDireito</td>
        </tr>
        <tr>
            <td>tecla alt+insert</td>
            <td>smartbeetle:f3+deslocadorDireito</td>
        </tr>
    </tbody>
</table>

<h3>Linhas Braille Seika</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>esquerda</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>direita</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>b3</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>b4</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>b5</td>
        </tr>
        <tr>
            <td>Leitura contínua</td>
            <td>b6</td>
        </tr>
        <tr>
            <td>tab</td>
            <td>b1</td>
        </tr>
        <tr>
            <td>shift+tab</td>
            <td>b2</td>
        </tr>
        <tr>
            <td>alt+tab</td>
            <td>b1+b2</td>
        </tr>
        <tr>
            <td>Menu do NVDA</td>
            <td>direita+esquerda</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
    </tbody>
</table>

<h3>Papenmeier BRAILLEX Novos Modelos</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>esquerda</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>direita</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>cima</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>baixo</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Anunciar o caractere atual em exploração</td>
            <td>l1</td>
        </tr>
        <tr>
            <td>Ativar o objeto de navegação atual</td>
            <td>l2</td>
        </tr>
        <tr>
            <td>Mover para a exploração plana/foco</td>
            <td>r1</td>
        </tr>
        <tr>
            <td>Anunciar o título</td>
            <td>l1+cima</td>
        </tr>
        <tr>
            <td>Anunciar a barra de Status</td>
            <td>l2+baixo</td>
        </tr>
        <tr>
            <td>Mover para o objeto pai</td>
            <td>up2</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>dn2</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>left2</td>
        </tr>
        <tr>
            <td>Mover para o objeto seguinte</td>
            <td>right2</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em célula braille</td>
            <td>linha de sensores superior</td>
        </tr>
    </tbody>
</table>

<table width="100%">
    <tbody>
        <tr>
            <td>tecla esc</td>
            <td>espaço com ponto 7</td>
        </tr>
        <tr>
            <td>tecla seta para cima</td>
            <td>espaço com ponto 2</td>
        </tr>
        <tr>
            <td>tecla seta para esquerda</td>
            <td>espaço com ponto 1</td>
        </tr>
        <tr>
            <td>tecla seta para direita</td>
            <td>espaço com ponto 4</td>
        </tr>
        <tr>
            <td>seta para baixo</td>
            <td>espaço com ponto 5</td>
        </tr>
        <tr>
            <td>tecla control</td>
            <td>lt+ponto2</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>lt+ponto3</td>
        </tr>
        <tr>
            <td>tecla control+esc</td>
            <td>espaço com ponto 1 2 3 4 5 6</td>
        </tr>
        <tr>
            <td>tecla tab</td>
            <td>espaço com ponto 3 7</td>
        </tr>
    </tbody>
</table>

<h3>Papenmeier Braille BRAILLEX Modelos Antigos</h3>
<p>
    Dispositivos que possuem EAB:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>left</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>right</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>up</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>dn</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Anunciar o caractere atual em exploração</td>
            <td>l1</td>
        </tr>
        <tr>
            <td>Ativar o atual objeto de navegação</td>
            <td>l2</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>r2</td>
        </tr>
        <tr>
            <td>Mover para a exploração plana/foco</td>
            <td>r1</td>
        </tr>
        <tr>
            <td>Anunciar título</td>
            <td>l1up</td>
        </tr>
        <tr>
            <td>Ler Barra de Status</td>
            <td>l2down</td>
        </tr>
        <tr>
            <td>Mover para o objeto pai</td>
            <td>up2</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>dn2</td>
        </tr>
        <tr>
            <td>Mover para o objeto seguinte</td>
            <td>right2</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>left2</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em célula braille</td>
            <td>faixa de sensores superior</td>
        </tr>
    </tbody>
</table>

<p>
    BRAILLEX Tiny:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Anunciar o caractere atual em exploração</td>
            <td>l1</td>
        </tr>
        <tr>
            <td>Ativar o atual objeto de navegação</td>
            <td>l2</td>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>left</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>right</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>up</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>dn</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>r2</td>
        </tr>
        <tr>
            <td>Mover para a exploração plana/foco</td>
            <td>r1</td>
        </tr>
        <tr>
            <td>Mover para o objeto pai</td>
            <td>r1+up</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>r1+dn</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>r1+left</td>
        </tr>
        <tr>
            <td>Mover para o objeto seguinte</td>
            <td>r1+right</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em célula braille</td>
            <td>faixa de sensores superior</td>
        </tr>
        <tr>
            <td>Anunciar título</td>
            <td>l1+up</td>
        </tr>
        <tr>
            <td>Anunciar barra de status</td>
            <td>l2+down</td>
        </tr>
    </tbody>
</table>

<p>
    BRAILLEX 2D Screen:
</p>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Anunciar o caractere atual em exploração</td>
            <td>l1</td>
        </tr>
        <tr>
            <td>Ativar o objeto de navegação atual</td>
            <td>l2</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>r2</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em célula braille</td>
            <td>faixa de sensores superior</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>up</td>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>left</td>
        </tr>
        <tr>
            <td>Mover para a exploração plana/foco</td>
            <td>r1</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>right</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>dn</td>
        </tr>
        <tr>
            <td>Mover para o próximo objeto</td>
            <td>left2</td>
        </tr>
        <tr>
            <td>Mover para o objeto pai</td>
            <td>up2</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>dn2</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>right2</td>
        </tr>
    </tbody>
</table>

<h3>HumanWare BrailleNote</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>back</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>advance</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>previous</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>next</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>previous+next</td>
        </tr>
        <tr>
            <td>Tecla seta acima</td>
            <td>espaço+ponto1</td>
        </tr>
        <tr>
            <td>Tecla seta abaixo</td>
            <td>espaço+ponto4</td>
        </tr>
        <tr>
            <td>Tecla seta a esquerda</td>
            <td>espaço+ponto3</td>
        </tr>
        <tr>
            <td>Tecla seta a direita</td>
            <td>espaço+ponto6</td>
        </tr>
        <tr>
            <td>Tecla page up</td>
            <td>espaço+ponto1+ponto3</td>
        </tr>
        <tr>
            <td>Tecla page down</td>
            <td>espaço+ponto4+ponto6</td>
        </tr>
        <tr>
            <td>Tecla home</td>
            <td>espaço+ponto1+ponto2</td>
        </tr>
        <tr>
            <td>Tecla end</td>
            <td>espaço+ponto4+ponto5</td>
        </tr>
        <tr>
            <td>Comando control+home</td>
            <td>espaço+ponto1+ponto2+ponto3</td>
        </tr>
        <tr>
            <td>Comando control+end</td>
            <td>espaço+ponto4+ponto5+ponto6</td>
        </tr>
        <tr>
            <td>Tecla espaço</td>
            <td>espaço</td>
        </tr>
        <tr>
            <td>Tecla enter</td>
            <td>espaço+ponto8</td>
        </tr>
        <tr>
            <td>Tecla backspace</td>
            <td>espaço+ponto7</td>
        </tr>
        <tr>
            <td>Tecla tab</td>
            <td>espaço+ponto2+ponto3+ponto4+ponto5 (espaço+t)</td>
        </tr>
        <tr>
            <td>Comando shift+tab</td>
            <td>espaço+ponto1+ponto2+ponto5+ponto6</td>
        </tr>
        <tr>
            <td>Tecla Windows</td>
            <td>espaço+ponto2+ponto4+ponto5+ponto6 (espaço+w)</td>
        </tr>
        <tr>
            <td>Tecla alt</td>
            <td>espaço+ponto1+ponto3+ponto4 (espaço+m)</td>
        </tr>
        <tr>
            <td>Alternar ajuda de entrada</td>
            <td>espaço+ponto1+ponto2+ponto5 (espaço+h)</td>
        </tr>
    </tbody>
</table>

<h3>EcoBraille</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>tecla</th>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>T2</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>T4</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>T1</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>T5</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>Sensor</td>
        </tr>
        <tr>
            <td>Ativar o objeto de navegação atual</td>
            <td>T3</td>
        </tr>
        <tr>
            <td>Alternar para o modo de exploração seguinte</td>
            <td>F1</td>
        </tr>
        <tr>
            <td>Mover para o objeto pai</td>
            <td>F2</td>
        </tr>
        <tr>
            <td>Alternar para o modo de exploração anterior</td>
            <td>F3</td>
        </tr>
        <tr>
            <td>Mover para o objeto anterior</td>
            <td>F4</td>
        </tr>
        <tr>
            <td>Anunciar o objeto atual</td>
            <td>F5</td>
        </tr>
        <tr>
            <td>Mover para o objeto seguinte</td>
            <td>F6</td>
        </tr>
        <tr>
            <td>Mover para o objeto em foco</td>
            <td>F7</td>
        </tr>
        <tr>
            <td>Mover para o primeiro objeto filho</td>
            <td>F8</td>
        </tr>
        <tr>
            <td>Mover foco ou cursor do sistema para a posição atual da exploração</td>
            <td>F9</td>
        </tr>
        <tr>
            <td>Anunciar localização do cursor de exploração</td>
            <td>F0</td>
        </tr>
        <tr>
            <td>Alternar vínculo do braille</td>
            <td>A</td>
        </tr>
    </tbody>
</table>

<h3>SuperBraille</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Deslocar a linha braille para trás</td>
            <td>menos do bloco numérico</td>
        </tr>
        <tr>
            <td>Deslocar a linha braille para frente</td>
            <td>mais do bloco numérico</td>
        </tr>
    </tbody>
</table>

<h3>Linhas Eurobraille Esys/Esytime/Iris</h3>
<table width="100%">
    <tbody>
        <tr>
            <th>Nome</th>
            <th>Tecla</th>
        </tr>
        <tr>
            <td>Rolar linha braille para trás</td>
            <td>interruptor1-6esquerdo, l1</td>
        </tr>
        <tr>
            <td>Rolar linha braille para frente</td>
            <td>interruptor1-6Direito, l8</td>
        </tr>
        <tr>
            <td>Mover para o foco atual</td>
            <td>interruptor1-6Esquerdo+interruptor1-6Direito, l1+l8</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>sensor</td>
        </tr>
        <tr>
            <td>Anunciar formatação de texto em cela braille</td>
            <td>sensorDuplo</td>
        </tr>
        <tr>
            <td>Mover para a linha anterior em exploração</td>
            <td>joystick1Cima</td>
        </tr>
        <tr>
            <td>Mover para a próxima linha em exploração</td>
            <td>joystick1Baixo</td>
        </tr>
        <tr>
            <td>Mover para o caractere anterior em exploração</td>
            <td>joystick1Esquerda</td>
        </tr>
        <tr>
            <td>Mover para o próximo caractere em exploração</td>
            <td>joystick1Direita</td>
        </tr>
        <tr>
            <td>Mudar para o modo de exploração anterior</td>
            <td>joystick1Esquerda+joystick1Cima</td>
        </tr>
        <tr>
            <td>Mudar para o próximo modo de exploração</td>
            <td>joystick1Direita+joystick1Baixo</td>
        </tr>
        <tr>
            <td>Apaga a última célula ou caractere braille inserido</td>
            <td>backSpace</td>
        </tr>
        <tr>
            <td>Transcreve qualquer entrada braille e pressiona a tecla enter</td>
            <td>backSpace+espaço</td>
        </tr>
        <tr>
            <td>tecla insert</td>
            <td>ponto3+ponto5+espaço, l7</td>
        </tr>
        <tr>
            <td>tecla delete</td>
            <td>ponto3+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla home</td>
            <td>ponto1+ponto2+ponto3+espaço, joystick2Esquerda+joystick2Cima</td>
        </tr>
        <tr>
            <td>tecla end</td>
            <td>ponto4+ponto5+ponto6+espaço, joystick2Direita+joystick2Baixo</td>
        </tr>
        <tr>
            <td>tecla setaParaEsquerda</td>
            <td>ponto2+espaço, joystick2Esquerda, setaParaEsquerda</td>
        </tr>
        <tr>
            <td>tecla setaParaDireita</td>
            <td>ponto5+espaço, joystick2Direita, setaParaDireita</td>
        </tr>
        <tr>
            <td>tecla setaParaCima</td>
            <td>ponto1+espaço, joystick2Cima, setaParaCima</td>
        </tr>
        <tr>
            <td>tecla setaParaDireita</td>
            <td>ponto6+espaço, joystick2Baixo, setaParaDireita</td>
        </tr>
        <tr>
            <td>tecla enter</td>
            <td>joystick2Centro</td>
        </tr>
        <tr>
            <td>tecla pageUp</td>
            <td>ponto1+ponto3+espaço</td>
        </tr>
        <tr>
            <td>tecla pageDown</td>
            <td>ponto4+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla numpad1</td>
            <td>ponto1+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad2</td>
            <td>ponto1+ponto2+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad3</td>
            <td>ponto1+ponto4+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad4</td>
            <td>ponto1+ponto4+ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad5</td>
            <td>ponto1+ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad6</td>
            <td>ponto1+ponto2+ponto4+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad7</td>
            <td>ponto1+ponto2+ponto4+ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad8</td>
            <td>ponto1+ponto2+ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpad9</td>
            <td>ponto2+ponto4+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadInsert</td>
            <td>ponto3+ponto4+ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadDecimal</td>
            <td>ponto2+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadDivide</td>
            <td>ponto3+ponto4+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadMultiplica</td>
            <td>ponto3+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadMenos</td>
            <td>ponto3+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadMais</td>
            <td>ponto2+ponto3+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla numpadEnter</td>
            <td>ponto3+ponto4+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla esc</td>
            <td>ponto1+ponto2+ponto4+ponto5+espaço, l2</td>
        </tr>
        <tr>
            <td>tecla tab</td>
            <td>ponto2+ponto5+ponto6+espaço, l3</td>
        </tr>
        <tr>
            <td>tecla shift+tab</td>
            <td>ponto2+ponto3+ponto5+espaço</td>
        </tr>
        <tr>
            <td>tecla printScreen</td>
            <td>ponto1+ponto3+ponto4+ponto6+espaço</td>
        </tr>
        <tr>
            <td>tecla pause</td>
            <td>ponto1+ponto4+espaço</td>
        </tr>
        <tr>
            <td>tecla aplicações</td>
            <td>ponto5+ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla f1</td>
            <td>ponto1+backspace</td>
        </tr>
        <tr>
            <td>tecla f2</td>
            <td>ponto1+ponto2+backspace</td>
        </tr>
        <tr>
            <td>tecla f3</td>
            <td>ponto1+ponto4+backspace</td>
        </tr>
        <tr>
            <td>tecla f4</td>
            <td>ponto1+ponto4+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla f5</td>
            <td>ponto1+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla f6</td>
            <td>ponto1+ponto2+ponto4+backspace</td>
        </tr>
        <tr>
            <td>tecla f7</td>
            <td>ponto1+ponto2+ponto4+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla f8</td>
            <td>ponto1+ponto2+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla f9</td>
            <td>ponto2+ponto4+backspace</td>
        </tr>
        <tr>
            <td>tecla f10</td>
            <td>ponto2+ponto4+ponto5+backspace</td>
        </tr>
        <tr>
            <td>tecla f11</td>
            <td>ponto1+ponto3+backspace</td>
        </tr>
        <tr>
            <td>tecla f12</td>
            <td>ponto1+ponto2+ponto3+backspace</td>
        </tr>
        <tr>
            <td>tecla windows</td>
            <td>ponto1+ponto2+ponto3+ponto4+backspace</td>
        </tr>
        <tr>
            <td>tecla capsLock</td>
            <td>ponto7+backspace, ponto8+backspace</td>
        </tr>
        <tr>
            <td>tecla numLock</td>
            <td>ponto3+backspace, ponto6+backspace</td>
        </tr>
        <tr>
            <td>tecla shift</td>
            <td>ponto7+espaço, l4</td>
        </tr>
        <tr>
            <td>Alternar tecla shift</td>
            <td>ponto1+ponto7+espaço, ponto4+ponto7+espaço</td>
        </tr>
        <tr>
            <td>tecla control</td>
            <td>ponto7+ponto8+espaço, l5</td>
        </tr>
        <tr>
            <td>Alternar tecla control</td>
            <td>ponto1+ponto7+ponto8+espaço, ponto4+ponto7+ponto8+espaço</td>
        </tr>
        <tr>
            <td>tecla alt</td>
            <td>ponto8+espaço, l6</td>
        </tr>
        <tr>
            <td>Alternar tecla alt</td>
            <td>ponto1+ponto8+espaço, ponto4+ponto8+espaço</td>
        </tr>
        <tr>
            <td>Alternar simulação de entrada de teclado HID</td>
            <td>esytime):l1+joystick1Baixo, esytime):l8+joystick1Baixo</td>
        </tr>
    </tbody>
</table>

<h3>BRLTTY</h3>
<table width="100%">
    <tbody>
        <tr>
            <td>Nome</td>
            <td>Comando BRLTTY</td>
        </tr>
        <tr>
            <td>Mover linha braille para trás</td>
            <td>fwinlt (caminha uma janela à esquerda)</td>
        </tr>
        <tr>
            <td>Mover linha braille para a frente</td>
            <td>fwinrt (Caminha uma janela à direita)</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha anterior</td>
            <td>lnup (sobe uma linha)</td>
        </tr>
        <tr>
            <td>Mover linha braille para a linha seguinte</td>
            <td>lndn (desce uma linha)</td>
        </tr>
        <tr>
            <td>Guiar para a cela braille</td>
            <td>route (leva o cursor ao caractere)</td>
        </tr>
    </tbody>
</table>

[Fonte](ftp://ftp.handytech.de/public/StartStick/files/nvda/documentation/pt_BR/keyCommands.html)
