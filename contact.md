---
title: "Contact"
order: 1
in_menu: true
---
Vous pouvez me contacter par email à l'adresse suivante : [alexandre.achain@gmail.com](mailto:alexandre.achain@gmail.com)

Ou via le formulaire ci-dessous :
<style>
/* Style de base du formulaire */
form {
  display: flex;
  flex-direction: column;
  width: 100%;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

/* Style des labels */
label {
  display: block;
  margin-top: 25px;
  margin-bottom: 5px;
  font-weight: bold;
}

/* Style des champs de saisie */
input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 3px;
  font-size: 16px;
}

/* Style du bouton d'envoi */
input[type="submit"] {
  background-color: #4CAF50;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  margin-top: 10px;
}

/* Style sur hover du bouton d'envoi */
input[type="submit"]:hover {
  background-color: #3e8e41;
}

/* Style du champ message (textarea) */
textarea {
  resize: vertical;
}

/* Style pour placeholder (texte grisé à l'intérieur des champs) */
input[type="text"]::placeholder,
input[type="email"]::placeholder,
textarea::placeholder {
  color: gray;
}
</style>
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