# WebSite_Status_HTML_JS

# Kodlar

```

<h1 id="fastuptime"> </h1>
<script>
    var fastuptime = document.getElementById("fastuptime");
    let site = "https://fastuptime.com";

    setInterval(() => {
        fetch(site).then(function(response) {
            if (response.status == 200) {
                fastuptime.innerHTML = "Site is online";
                fastuptime.style.color = "green";
                fastuptime.title = "Site is online - " + site;
            } else {
                fastuptime.innerHTML = "Site is offline";
                fastuptime.style.color = "red";
                fastuptime.title = "Site is offline - " + site;
            }
        }).catch(function(error) {
                fastuptime.innerHTML = "Site is offline";
                fastuptime.style.color = "red";
                fastuptime.title = "Site is offline - " + site;
        });
    }, 1000);
</script>

```

# Resimler

![image](https://user-images.githubusercontent.com/63351166/211154240-f4cdc900-a322-4743-b95b-aa85653bb9c6.png)
![image](https://user-images.githubusercontent.com/63351166/211154254-a0c0140d-d2cf-4ec0-a3b5-9e55a104b5a5.png)


---
- ✨ [Destek İçin](https://fastuptime.com) <br>
- 💕 [Discord](https://fastuptime.com/discord)<br>
- 🎖️ [FasterHost Technology](https://fasterhost.tech/)<br>
- ✨ İletişim için [Tıkla!](mailto:fastuptime@gmail.com)<br>

# License
- Its protected by Creative Commons ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/))

<a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" title="BYNCSA40"><img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png"></a>
