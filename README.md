
Script per aggiornare Gentoo Linux
==================================
Synopsis
 <p> Aggiorna automaticamente Gentoo Linux in più fasi:</p>
  <p>sync</p>
   <p>update</p>
    <p>preservedrebuild</p>
     <p>depclean</p>
      <p>revdeprebuild</p>
================
<p>Utilizzo:</p>
================
  <p>gentooupdate [opzioni]</p>
<p></p>
<p>Opzioni:</p>
  <p>-a true</p>
    <p>Interrompi se ci sono notizie non lette o se emerge è già in esecuzione.</p>
  <p>-d "--depclean"</p>
   <p> Gli argomenti passati a revdep-rebuild durante la fase revdeprebuild.</p>
  <p>-e ""</p>
   <p> Gli argomenti passati a revdep-rebuild durante la fase revdeprebuild.</p>
 <p> -h</p>
    <p>Mostra questo messaggio di aiuto ed esci.</p>
  <p>-n N</p>
    <p>Imposta la precisione su N (default 0).</p>
  <p>-r "@preserved-rebuild"</p>
   <p> Gli argomenti passati ad emerge durante la fase di preservedbuild.</p>
  <p>-s "--sync"</p>
    <p>Gli argomenti passati ad emerge durante la fase di sync.</p>
  <p>-u "-uDN --with-bdeps=y world"</p>
    <p>Gli argomenti passati ad emerge durante la fase di update.</p>
<p></p>
<p>Esempi:</p>
 <p> gentooupdate -a false</p>
 <p> gentooupdate -n 20 -u "-uDN --with-bdeps=y --keep-going world"</p>
<p></p>
<p>Versione:</p>
  <p>Gentoo Update 1.1.1.1</p>
  <p>File Originale Nathan Shearer</p>
  <p>Editore Cristian Pozzessere</p>
  <p>Distribuito mediante  GNU General Public License 2.0</p>
