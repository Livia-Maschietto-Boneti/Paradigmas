#11. Construa uma cadeia de influência que passe por ALGOL, Pascal e C. Depois contraste essa linhagem imperativa com a proposta declarativa de Prolog.

ALGOL 68 trouxe importantes inovações para o projeto de linguagens, principalmente a ortogonalidade, que permite combinar recursos de forma independente e previsível, além de tipos definidos pelo usuário e vetores dinâmicos.
Seu principal sucessor, Pascal, foi criado para o ensino e teve grande impacto nas universidades nos anos 70, destacando-se pela simplicidade e expressividade.

#12. Modele em linguagem natural uma pequena base Prolog com dois fatos, uma regra e uma consulta. Explique por que isso representa programação lógica, não apenas armazenamento de dados.

Prolog é uma linguagem de programação lógica em que os programas são formados por fatos, regras e consultas. Por exemplo, dois fatos podem ser pai(Carlos, João) e pai(Maria, Ana), uma regra pode ser avo(X, Z):- pai(X, Y), pai(Y, Z) e uma consulta pode ser pai(Joao, Maria).
Isso representa programação lógica porque o programa não descreve exatamente como o resultado deve ser calculado, mas fornece informações e regras para que o computador faça inferências. Assim, ao receber uma consulta, o Prolog utiliza o processo de resolução para verificar se ela pode ser provada.

#13. Ada resultou de requisitos e projeto em grande escala. Analise como
confiabilidade, tipos, pacotes e concorrência se relacionam ao domínio
de sistemas críticos.

A Ada foi criada a partir de um grande projeto para atender principalmente a sistemas em que a confiabilidade é crítica, como aviônica, controle de tráfego aéreo e transportes. Sua estrutura busca aumentar a segurança por meio de tipos fortes, que ajudam a detectar erros, e pacotes, que organizam e protegem dados e operações. Além disso, possui recursos de concorrência, importantes para sistemas que precisam executar várias tarefas ao mesmo tempo de forma controlada. Apesar de ser considerada extensa e complexa, essas características fazem Ada ser adequada para sistemas críticos, nos quais falhas podem causar grandes prejuízos. A partir do Ada 95, também foram adicionados recursos de orientação a objetos, como herança e polimorfismo.

#15. A primeira aplicação de Java não foi a Web, mas a Web impulsionou
sua adoção. Explique como mudanças de contexto podem reposicionar
uma linguagem.

Java foi criada para atender a uma necessidade que outras linguagens não supriam, tendo como um de seus principais objetivos a confiabilidade, especialmente para produtos eletrônicos de consumo. Porém, os produtos que utilizariam Java inicialmente não chegaram a ser comercializados. A partir de 1993, com o crescimento da World Wide Web e dos navegadores gráficos, Java passou a ser muito utilizada na Web. Os applets Java, pequenos programas executados dentro dos navegadores e exibidos em páginas Web, tornaram-se populares durante a década de 1990. Assim, nos primeiros anos de sua popularidade, a Web foi a principal aplicação de Java.
Mudanças de contexto podem fazer com que uma linguagem passe a ser utilizada em uma área diferente daquela para a qual foi originalmente criada.

#18. Diferencie XSLT e JSP quanto a entrada, processamento e saída. Por
que ambas podem ser chamadas de linguagens híbridas de marcação e
programação?
    
XSLT é uma linguagem híbrida de marcação e programação, criada pelo W3C para transformar documentos XML em outros documentos, como HTML. Ela utiliza templates e instruções de transformação para definir como os dados serão processados. Sua entrada é um documento XML junto com um documento XSLT, o processamento é feito pelo processador XSLT e a saída é outro documento, como XML ou HTML.
JSTL também é uma linguagem híbrida, usada em conjunto com JSP para criar páginas Web dinâmicas. Seus elementos controlam o processamento no servidor e ajudam a definir como o conteúdo de saída será gerado. No JSP, a entrada é um documento JSP, normalmente misturando HTML e Java; o servidor processa esse documento, convertendo-o em um servlet, e a saída é o conteúdo Web gerado para o navegador.
Ambas também possuem recursos de programação, por isso são consideradas linguagens híbridas de marcação-programação.



