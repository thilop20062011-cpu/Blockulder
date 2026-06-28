# Blockulder
A visual block coding "library" made with AI | 
only modify things if you know what are you doing | 
the entire thing is inside that html file | 
demo at http://thiserv.xo.je/pages/blockulder/index.html | 
common questions:
how do i create a block?
type
Blockulder.definirBloco({
    category: 'block', type: 'block', color: '#2196f3',
    elements: ['this is a text'], //types of elements: text,statement,slot,number // uses: Criar.text('NAME', 'text') | Criar.statement('NAME') | Criar.slot('NAME) | Criar.number('NAME', '0')
    generator: (bloco) => {
        // put your block code here
});
