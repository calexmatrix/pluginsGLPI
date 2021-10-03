# pluginsGLPI
Solução para erro no formulário no campo anexar * (obrigatorio) no Plugin Formcreator

Modificação - filefield.class.php - (...\parvidesk\plugins\formcreator\inc\field\filefield.class.php) Essa alteração corrige o erro da tela branca ao abrir chamados por formularios(plugin formcreator) onde o anexo deve ser obrigatorio no chamado, no caso quando o anexo não era adicionado e ao clicar em salvar o formulario totalmente preenchido, deveria exibir o alerta de erro. Após correção o mesmo exibe a tela de erro.

https://github.com/calexmatrix/pluginsGLPI/blob/main/Formcreator_7.png








