Mascara CPF

Script JS que gera automaticamente os pontos e o traço do CPF.

COMO USAR

Declarar no código HTML antes de terminar a etiqueta Body

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.mask/1.14.11/jquery.mask.min.js"></script>
    <script src="app.js"></script>
    
Na etiqueta input colocar um id para identificar aonde vai ser colocado o CPF.
   -->(Por exemplo id="cpf").
    
Colocar esse id no script app.js assim,
   --> $("#cpf").mask("000.000.000-00");

DEV: Jorge Edo. Hernández - Grupo Alpha

Github: @jorgehernandezch
