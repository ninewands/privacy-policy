---
layout: default
title: Ninewands Privacy Policy
lang: en
---

<script>
document.addEventListener("DOMContentLoaded", function() {
    let userLang = navigator.language || navigator.userLanguage;
    userLang = userLang.split('-')[0];

    const supportedLanguages = ['ko'];

    if (supportedLanguages.includes(userLang)) {
        window.location.href = `./${userLang}/`;
    } else {
        window.location.href = `./en/`;
    }
});
</script>
