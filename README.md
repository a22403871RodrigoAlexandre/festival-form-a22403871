# festival

Descreva aqui as alterações/correções que fez

Foi adicionada a ordenação dos dias por ordem crescente utilizando .order_by('data') na view.

A linha ordering = ["dia__data", "hora"] no modelo Concerto permite ordenar automaticamente os concertos pela data do dia e, dentro de cada dia, pela hora.

Foi atualizado o formulário de concerto (ConcertoForm) para incluir todos os campos: banda, dia, hora e palco, permitindo editar todos os atributos.

Foi implementada a funcionalidade de apagar concertos, incluindo a criação da url, da view e de um form com método POST no template HTML.

Foi implementada a funcionalidade de criar concertos, através da criação da view, url e template correspondente.

Foi adicionado ao modelo Palco o campo booleano acessibilidade_mobilidade_reduzida.

Foi realizada a migração da base de dados após a alteração ao modelo Palco.

Foi atualizada a página dos palcos para mostrar a capacidade, o número total de concertos agendados e o símbolo, quando existe acessibilidade para mobilidade reduzida.

Foi implementada também a funcionalidade de editar palcos, incluindo a criação do PalcoForm, da view, da url e do template.
