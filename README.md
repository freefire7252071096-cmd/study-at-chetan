<h2>🔐 Unlock Your Batch</h2>

<input
  type="password"
  id="batchCode"
  placeholder="Enter Batch Code"
>

<button onclick="unlockBatch()">
  Unlock Batch
</button>

<p id="message"></p>

<a
  id="batchLink"
  href="https://www.pw.live/"
  target="_blank"
  hidden
>
  Open Official PW Website
</a>

<script>
function unlockBatch() {
  const code = document.getElementById("batchCode").value;
  const message = document.getElementById("message");
  const link = document.getElementById("batchLink");

  if (code === "STUDY2027") {
    message.textContent = "Batch link unlocked!";
    link.hidden = false;
  } else {
    message.textContent = "Invalid batch code!";
    link.hidden = true;
  }
}
</script># study-at-chetan
Study@Chetan - Free Study Resources
