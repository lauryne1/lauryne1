<template>
    <div class="flex flex-col tiems-center justify-center">
        <h2>Contactez-moi</h2>
        <div class="flex flex-col bg-red-500
        ">
            <form id="contact-form">
                <input type="text" id="name" name="name" placeholder="Votre nom" required>
                <input type="email" id="email" name="email" placeholder="Votre email" required>
                <input type="text" id="subject" name="subject" placeholder="Sujet">
                <textarea id="message" name="message" placeholder="Votre message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>   

