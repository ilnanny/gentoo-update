# gentoo-update
Script per aggiornare Gentoo Linux
==================================
Synopsis
  Aggiorna automaticamente Gentoo Linux in più fasi:
    sync
    update
    preservedrebuild
    depclean
    revdeprebuild

Usage:
  gentooupdate [options]

Options:
  -a true
    Interrompi se ci sono notizie non lette o se emerge è già in esecuzione.
  -d "--depclean"
    Gli argomenti passati a revdep-rebuild durante la fase revdeprebuild.
  -e ""
    Gli argomenti passati a revdep-rebuild durante la fase revdeprebuild.
  -h
    Mostra questo messaggio di aiuto ed esci.
  -n N
    Imposta la precisione su N (default 0).
  -r "@preserved-rebuild"
    Gli argomenti passati ad emerge durante la fase di preservedbuild.
  -s "--sync"
    Gli argomenti passati ad emerge durante la fase di sync.
  -u "-uDN --with-bdeps=y world"
    Gli argomenti passati ad emerge durante la fase di update.

Esempi:
  gentooupdate -a false
  gentooupdate -n 20 -u "-uDN --with-bdeps=y --keep-going world"

Versione:
  Gentoo Update 1.1.1.1
  File Originale Nathan Shearer
  Editore Cristian Pozzessere
  Distribuito mediante  GNU General Public License 2.0
