# Lumera — site para GitHub e Vercel

Este pacote contém a versão estática da landing page da Lumera, incluindo a hero interativa, as animações e a navegação com rolagem suave.

## Colocar no GitHub

1. Crie um repositório vazio no GitHub.
2. Extraia o arquivo `Lumera-Vercel.zip`.
3. Envie **o conteúdo da pasta extraída** para a raiz do repositório.

O arquivo `index.html` deve permanecer na raiz.

## Publicar pela Vercel

1. Na Vercel, selecione **Add New > Project**.
2. Importe o repositório criado no GitHub.
3. Use **Framework Preset: Other**.
4. Deixe **Build Command** vazio.
5. Use `.` em **Output Directory**, caso a Vercel solicite esse campo.
6. Clique em **Deploy**.

As imagens e as fontes são carregadas por serviços externos, portanto o site publicado precisa de acesso à internet.
