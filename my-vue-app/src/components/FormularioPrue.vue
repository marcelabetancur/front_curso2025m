<template>
    <form action="procesar.php" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <label for="email">Correo:</label>
        <input type="email" id="email" name="email" required>
        <label for="edad">Edad:</label>
        <input type="number" id="edad" name="edad" min="1" max="100">
        <label for="genero">Genero:</label>
        <select id="genero" name="genero">
            <option value="hombre">Hombre</option>
            <option value="mujer">Mujer</option>
        </select>
        <label>
            <input type="checkbox" name="terminos"> Acepto los terminos y condiciones
        </label>
        <button type="submit">Enviar</button>
    </form>

</template>

<script setup>

</script>

<style></style>