<?php
  $READ_COOKIE = ($_COOKIE['READ'] ?? '');
  if( $READ_COOKIE !== '1' ){
?>
    <div id="cookies" class="alert alert-warning alert-dismissible fade show fixed-bottom my-0 fw-bold" role="alert">
      Durch das Nutzen dieser Seite erkl&auml;ren Sie, mit den <a href="datenschutz.php">Datenschutzrichtlinien</a> einverstanden zu sein!
      <button type="button"  onclick="acceptCookies();" class="close border color1 p-2 m-1 rounded fw-bold btn-secondary btn-lg border-3 border-dark" data-dismiss="alert" aria-label="Close">
        <span aria-hidden="true">&nbsp;&nbsp;&nbsp;Akzeptieren&nbsp;&nbsp;&nbsp;</span>
      </button>
    </div>
    <script>
      function acceptCookies() {
        var cookiesElement = document.getElementById("cookies");
        cookiesElement.style.display = "none";

        document.cookie = "READ=1;path=/;SameSite=Lax';";
      }
    </script>
<?php
  }
?>
