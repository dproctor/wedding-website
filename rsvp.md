---
title: rsvp
layout: page
permalink: /rsvp/
---
<style>
form {
  margin-top: 20px;
  text-align: left;
}
td {
  padding: 5px;
}
#submit-btn {
  margin-top: 10px;
  background-color: #3E120E;
  color: #FAECEA;
  font-family: 'Lato', sans-serif;
}
#rsvp-form.submitted table {
  background-color: #55555555;
}
#rsvp-form.submitted input {
  pointer-events: none;
}
#rsvp-form.submitted select {
  pointer-events: none;
}
#rsvp-form.submitted #submit-btn {
  pointer-events: none;
}
#rsvp-form #submit-btn:after {
  content: "Submit";
}
#rsvp-form.submitted #submit-btn:after {
  content: "RSVP received!";
}
</style>
<script type="text/javascript">
function markFormAsSubmitted() {
  var form = document.getElementById('rsvp-form');
  if (!form) {
    return;
  }
  form.classList.add('submitted');
}
</script>
<h1> rsvp </h1>
<iframe name="redirect" style="display:none;"></iframe>
<form id="rsvp-form" action="https://docs.google.com/forms/u/0/d/e/1FAIpQLScqvqgEScOPdPIzU9tcuqQW2vE5z_70xHbqrzEf-1G5ZqAm8Q/formResponse"
  method="post" target="redirect" onsubmit="markFormAsSubmitted();">

  <table>
  <tr>
  <td> <label for="name">Name:</label> </td>
  <td> <input type="text" id="name" name="entry.26404874"> </td>
  </tr>

  <tr>
  <td> <label for="attending">Attending:</label> </td>
  <td> <select id="attending" name="entry.1134362660">
    <option value="beef">Yes</option>
    <option value="fish">No</option>
  </select> </td>
  </tr>

  <tr>
  <td> <label for="other-adults">Other adults:</label> </td>
  <td> <input type="text" id="other-adults" name="entry.1823978788"> </td>
  </tr>

  <tr>
  <td> <label for="other-kids">Other kids:</label> </td>
  <td> <input type="text" id="other-kids" name="other-kids"> </td>
  </tr>

  <tr>
  <td> <label for="dinner">Dinner:</label> </td>
  <td> <select id="dinner" name="entry.1565730477">
    <option value="beef">Beef</option>
    <option value="fish">Fish</option>
    <option value="vegetarian">Vegetarian</option>
  </select> </td>
  </tr>

  <tr>
  <td> <label for="lodging">Where are you staying? (If you've already booked) </label> </td>
  <td> <input type="text" id="lodging" name="entry.1795561058"> </td>
  </tr>

  </table>
  <div style="text-align:center">
    <button class="button" id="submit-btn" type="submit"></button>
  </div>

</form>
