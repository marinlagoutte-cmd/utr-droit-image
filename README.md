# Autorisation droit à l'image — Ultra Tour de la Ria

Page que les participants ouvrent avec un QR code pour lire, remplir et signer au doigt l'autorisation de droit à l'image
(shooting des 14 & 15 novembre 2026).

- `index.html` : la page. Le téléphone remplit le PDF vierge et l'envoie à un script Google, qui le range dans le Drive de l'association.
- `Majeur.pdf`, `Mineur.pdf` : les deux autorisations vierges.
- `pdf-lib.min.js` : bibliothèque [pdf-lib](https://pdf-lib.js.org) 1.17.1 (licence MIT, voir `LICENSE-pdf-lib.md`).

Aucune donnée de signataire n'est stockée ici.
