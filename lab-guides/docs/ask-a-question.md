# Ask a Question

[:material-arrow-left: Back to Home](index.md){ .md-button }

Have a question about a badge, a machine, or your project? Fill this out and it goes to **Jonathan Van Hyning**, our lab tech.

<form class="ask-form" id="ask-form" novalidate>
  <label for="ask-name">Your name</label>
  <input id="ask-name" name="name" type="text" autocomplete="name" required>

  <label for="ask-topic">What is it about?</label>
  <select id="ask-topic" name="topic">
    <option>3D Printing</option>
    <option>Laser Cutting</option>
    <option>Soldering</option>
    <option>Onshape</option>
    <option>Something else</option>
  </select>

  <label for="ask-question">Your question</label>
  <textarea id="ask-question" name="question" rows="6" required></textarea>

  <p class="ask-form__error" id="ask-error" role="alert" hidden>Please add your name and your question.</p>

  <button type="submit" class="md-button md-button--primary">Send to Jonathan</button>
</form>

!!! info "What happens when you click Send"
    Your email app opens with the message already written to Jonathan. **Check it, then click Send in your email app.**
    Use your **WCC email** so he can write back.

    Email app didn't open? Email him directly at [JVanHyning@whatcom.edu](mailto:JVanHyning@whatcom.edu).

<script>
(function () {
  var form = document.getElementById("ask-form");
  if (!form) return;
  form.addEventListener("submit", function (e) {
    e.preventDefault();
    var name = document.getElementById("ask-name").value.trim();
    var topic = document.getElementById("ask-topic").value;
    var question = document.getElementById("ask-question").value.trim();
    var err = document.getElementById("ask-error");
    if (!name || !question) { err.hidden = false; return; }
    err.hidden = true;
    var subject = "Lab question: " + topic + " (" + name + ")";
    var body = "Hi Jonathan,\n\n" + question + "\n\nThanks,\n" + name;
    window.location.href = "mailto:JVanHyning@whatcom.edu?subject=" +
      encodeURIComponent(subject) + "&body=" + encodeURIComponent(body);
  });
})();
</script>
