# minhabiblioteca_downloader
Downloader de livros da minhabiblioteca.com.br

Ajustado do https://github.com/qstore2/vitalsource-download

1. Firefox install "Export Cookies"
2. Vá para https://jigsaw.vitalsource.com/login/setup?return=%2F
3. Login
   Depois do login, você verá algo como "Something went wrong"
4. Vá para https://jigsaw.minhabiblioteca.com.br/books/<VBID>/content/image/1.jpg
   (reponha <VBID> com o atual (id) do livro
   cheque se o livro está ok 
5. Click em "Export cookies" plugin, exporte minhabiblioteca.com.br para "cookies.txt"
6. Execute "dl.sh <VBID>"
   * para achar o VBID, click clique no (i) na versão web.

## if the image shows "Please refresh your browser", starts from step 2 to step 5 again (re-download the cookies), edit the STARTPAGE in .sh file to continue the page (don't worry about ENDPAGE)
