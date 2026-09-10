# Formato GSY CustomIgnis — point list distribuita

Questo repo ospita **solo** l'artefatto pubblico: `banlist.json` firmato e la
sua firma `banlist.json.sig`. Non è un progetto software e non si modifica a
mano — viene generato e pubblicato dal repo privato del vault tramite una
GitHub Action (`workflow_dispatch` manuale), firmato con Ed25519.

- Ogni release è un commit: la cronologia di questo repo *è* il changelog
  del formato.
- Il client verifica la firma **prima** di leggere il contenuto, con una
  chiave pubblica compilata al suo interno.
- `LICENSE` copre l'uso della point list in sé (giocarci, costruire deck,
  farci contenuti). Non copre il codice del client né altro software.

Nessuna issue/PR gestita qui: è un artefatto di build, non un progetto con
cui contribuire.
