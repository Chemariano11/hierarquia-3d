[LEIA-ME.md](https://github.com/user-attachments/files/35362187/LEIA-ME.md)
# Hierarquia do sistema em 3D – versão para publicação na web

Este `index.html` é a ilustração 3D "Do componente ao suprassistema" (voo de drone pela estação de bombeamento), em um único arquivo, pronta para qualquer hospedagem de páginas estáticas. Não precisa de servidor nem instalação.

**Endereço previsto:** https://chemariano11.github.io/hierarquia-3d/

## Publicar no GitHub Pages

1. Em https://github.com, clique em **New repository**. Nome sugerido: `hierarquia-3d`. Marque **Public** e clique em **Create repository**.
2. Na página do repositório vazio, clique em **uploading an existing file**, arraste o `index.html` (e, se quiser, este `LEIA-ME.md`) e clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em *Build and deployment*, escolha **Source: Deploy from a branch**, **Branch: main** e pasta **/ (root)**. Clique em **Save**.
4. Aguarde 1 a 2 minutos e recarregue Settings → Pages: aparecerá o endereço `https://chemariano11.github.io/hierarquia-3d/`.
5. Coloque esse endereço no Moodle (recurso **URL**) e, se quiser, no kit do Encontro 1 (sexta, Módulo 1).

**Para atualizar:** no repositório, **Add file → Upload files**, envie o novo `index.html` com o mesmo nome e confirme. O endereço continua o mesmo.

**Atenção ao nome do arquivo:** precisa ser exatamente `index.html`. Se o navegador salvar como `index_1.html` ou `index (1).html`, o site dá erro 404; renomeie antes de enviar.

## Como os alunos usam

- **Rolar o mouse** aproxima ou afasta (zoom); **arrastar** gira a vista; **setas ← →** trocam de nível.
- **Botão "Voo"**: percorre os seis níveis do micro ao macro; no topo, o botão inverte e faz a descida (macro → micro).
- **Escada à direita**: clique num nível para ir direto a ele. A ficha mostra definição, exemplo na estação, olhar de confiabilidade e "contém / faz parte de".
- A **linha tracejada amarela** é a fronteira de cada item; a do nível de baixo continua visível, mais clara.

## Observações

- A biblioteca 3D (three.js r128) vem de cdnjs.cloudflare.com e as fontes do Google Fonts: é preciso internet. Sem as fontes, o navegador usa fontes padrão.
- Funciona em computador, tablet e celular (no celular, use o controle deslizante para o zoom).
- O repositório público deixa o código visível (o GitHub Pages gratuito exige repositório público).
- OneDrive e SharePoint não servem para hospedar: eles baixam ou bloqueiam páginas HTML com programas. Alternativa sem GitHub: Netlify Drop (https://app.netlify.com/drop).

## Material relacionado

- Modelo 3D da estação de bombeamento: https://chemariano11.github.io/estacao-3d/
- Simulador RAM-RBD: https://chemariano11.github.io/simulador-ram-rbd/
