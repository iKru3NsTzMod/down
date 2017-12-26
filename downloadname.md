function nomeArquivo(link) {
 var lnk = link;
 lnk = lnk.substr(lnk.search("loads/")+6);
 return lnk;
}
var linkpro1 = window.parent.document.location.href;
nomearq = nomeArquivo(linkpro1);

document.write("<B>Nome do arquivo:</B> "+nomearq+"");
