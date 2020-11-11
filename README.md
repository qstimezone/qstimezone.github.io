<html>
    <style>
        h1 {text-align: center; font-family: 'arial'; vertical-align: middle;}
    </style>

    <h1 id="text">Loading...</h1>

    <script>
        var timezone=Intl.DateTimeFormat().resolvedOptions().timeZone
        navigator.clipboard.writeText(timezone)

        document.getElementById("text").innerHTML=timezone
    </script>
</html>
