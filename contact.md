---
title: "Contact"
order: 1
in_menu: true
---
Vous pouvez me contacter par email à l'adresse suivante : [alexandre.achain@gmail.com](mailto:alexandre.achain@gmail.com)

Ou via le formulaire ci-dessous :
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/{form_id}" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Nom complet</label>
    <input type="text" name="name" id="full-name" placeholder="Prénom et Nom de Famille" required="true">
    <label for="email-address">Addresse Email</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="true">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Ajouter votre message ici !" required="true"></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Envoyer">
</form> 