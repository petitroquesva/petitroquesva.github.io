Adhésion au club:

+ Télécharger, remplir et transmettre la [fiche inscription 2023-2024](resources/Fiche-inscription-2023-2024.docx)



+ Pour une licence A (compétition):
    + lire le Questionnaire Santé relatif [aux majeurs](resources/2-questionnaire_majeur.pdf) ou [aux mineurs](resources/2-questionnaire_mineur.pdf)
        + si __NON__ à toutes les réponses, fournir [l'attestation de réponse négative](resources/2-Attestation_negative.pdf)
        + si __OUI__ à au moins une réponse, fournir un __certificat médical de moins de 3 ans__.

<div class="alert alert-dismissible alert-success">
  Si le certificat médical a été établi il y a <strong>2 ans</strong> pour une autre activité sportive, il est également <strong>valable</strong> !.
</div>



<ul class="nav nav-tabs" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link active" data-bs-toggle="tab" href="#licenceA" aria-selected="true" role="tab">Licence A</a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" data-bs-toggle="tab" href="#licenceB" aria-selected="false" role="tab" tabindex="-1">Licence B</a>
  </li>
</ul>
<div id="myTabContent" class="tab-content">
  <div class="tab-pane fade active show" id="licenceA" role="tabpanel">
<div>
<li> lire le Questionnaire Santé relatif <a href="./../resources/2-questionnaire_majeur.pdf">aux majeurs</a> ou <a href="./../resources/2-questionnaire_mineur.pdf">aux mineurs</a></li>
<li> si <strong>NON</strong> à toutes les réponses, <a href="./../resources/2-Attestation_negative.pdf">l'attestation de réponse négative</a></li>
<li> si <strong>OUI</strong> à au moins une réponse, fournir un <strong>certificat médical de moins de 3 ans</strong>.</li>
</div>
<br/>
<div class="alert alert-dismissible alert-success">
  Si le certificat médical a été établi il y a <strong>2 ans</strong> pour une autre activité sportive, il est également <strong>valable</strong> !.
</div>

  </div>
  <span class="tab-pane fade" id="licenceB" role="tabpanel">
    <p>Food truck fixie locavore, accusamus mcsweeney's marfa nulla single-origin coffee squid. Exercitation +1 labore velit, blog sartorial PBR leggings next level wes anderson artisan four loko farm-to-table craft beer twee. Qui photo booth letterpress, commodo enim craft beer mlkshk aliquip jean shorts ullamco ad vinyl cillum PBR. Homo nostrud organic, assumenda labore aesthetic magna delectus mollit.</p>
  </span>
</div>
                  

```mermaid
flowchart TD
    id0[Télécharger, remplir et transmettre <br/>la fiche inscription 2023-2024]
    id0 --> id1{Licence A <br/>ou <br/>licence B ?} -- Licence A --> id2[Lire le <br/>Questionnaire Santé]
    id2 -- Pour les majeurs --> id2a[Questionnaire majeur]
    id2 -- Pour les mineurs --> id2b[Questionnaire mineur]
    id2a & id2b -- NON<br/>à toutes les réponses ? --> id3[Fournir l'attestation<br/>de réponse négative]
    id2a & id2b -- OUI<br/>à au moins une réponse ? --> id4[Fournir un certificat médical<br/>de moins de 3 ans]
    id1 -- Licence B --> id5[Régler votre <br/>cotisation]
    id3 --> id5[Régler votre <br/>cotisation]
    id4 --> id5[Régler votre <br/>cotisation]
    click id0 "resources/Fiche-inscription-2023-2024.docx"
    click id2a "resources/2-questionnaire_majeur.pdf"
    click id2b "resources/2-questionnaire_mineur.pdf"
    click id3 "resources/2-Attestation_negative.pdf"
```