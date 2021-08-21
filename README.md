#### ORFfinder_results

Esse script simples pega um arquivo .fasta com sequências diversas, abre o ORFfinder e salva a primeira ORF (a mais próvavel) em dois outputs diferentes a região codificante (Do ATG ao Stopcodon): um output com a região traduzida e outra versão com nucleotídeos, conservando a tag original da sequência.

* como usar:

No prompt de comando, digitar python ORFfinder_results.py nome_do_arquivo output_aminoacidos output_nucletideos

OBS: Sempre dar uma olhada no andamento do script, pois o site ORFfinder sempre possui alguns delays em retornar os resultados e, por causa disso, o script pode bugar!
