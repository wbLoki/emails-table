<script lang="ts">
  export let recipients

  let emailList = recipients;
  var mailWidth = document.getElementById("mails");
  
  const containerWidth = document.getElementById("mails");
  
  // for (let i = recipients.length; i > 0; i--) {
  //   if (mailWidth < )
    
  // }
  // console.log(emailList);
  console.log(mailWidth);
</script>

<span id="mails">{recipients}</span>