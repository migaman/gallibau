---
layout: default
form: true
---

<p>Setzen Sie sich mit uns in Verbindung. Füllen Sie das Formular aus und wir werden so schnell wie möglich antworten!</p>
<form name="sentMessage" id="contactForm" novalidate>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Name</label>
      <input type="text" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Bitte Namen eingeben...">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>E-Mail Adresse</label>
      <input type="email" class="form-control" placeholder="E-Mail Adresse" id="email" required data-validation-required-message="Bitte E-Mail eingeben...">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Telefon</label>
      <input type="phone" class="form-control" placeholder="Telefon" id="phone">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Nachricht</label>
      <textarea rows="5" class="form-control" placeholder="Nachricht" id="message" required data-validation-required-message="Bitte Nachricht eingeben..."></textarea>
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <br>
  <div id="success"></div>
  <div class="form-group">
    <button type="submit" class="btn btn-primary" id="sendMessageButton">Senden</button>
  </div>
</form>
