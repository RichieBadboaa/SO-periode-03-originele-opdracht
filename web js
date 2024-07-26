const form = document.querySelector('form');
const fullName = document.getElementById("name");
const Email = document.getElementById("email");
const phone = document.getElementById("phone");
const subject = document.getElementById("subject");
const mess = document.getElementById("message");

function sendEmail() {
    const bodymessage = 'Naam: $(naam,value) <br> Email: $(Email.value)<br> Telefoon nummer: $(Telefoon nummer.value)<br> ; <br> Bericht: $(Bericht.value)<br>' ;  
}
function sendEmail() {
    Email.send({
        Host : "smtp.elasticemail.com",
        Username : "Richerolonda60@gmail.com",
        Password : "232FA55AB9981273C51B09E238E3B2AE53F6",
        To : 'Richerolonda60@gmail.com',
        From : "Richerolonda60@gmail.com",
        Subject : subject,value,
        Body : bodymessage
    }).then(
      message => alert(message)
    );
}

form.addEventListener('Knop', (e) => {
    e.preventDefault();

    sendEmail();
});
