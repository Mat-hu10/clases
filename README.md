<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Registro Veterinaria</title>
</head>
<body style="font-family: sans-serif; display: flex; justify-content: center; padding-top: 50px; background-color: #f4f4f9;">

    <div style="background: white; padding: 20px; border-radius: 8px; border: 1px solid #ccc; width: 300px;">
        <h2 style="text-align: center; color: #2c3e50;">🐾 Veterinaria</h2>
        
        <form method="dialog">
            <label>Nombre del Dueño:</label><br>
            <input type="text" placeholder="Ej. Carlos" style="width: 100%; margin-bottom: 15px;"><br>

            <label>Nombre de la Mascota:</label><br>
            <input type="text" placeholder="Ej. Toby" style="width: 100%; margin-bottom: 15px;"><br>

            <button type="submit" onclick="document.getElementById('ventanaExito').showModal()" 
                    style="width: 100%; padding: 10px; background-color: #007bff; color: white; border: none; border-radius: 4px; cursor: pointer;">
                Registrarme
            </button>
        </form>
    </div>

    <dialog id="ventanaExito" style="border: none; border-radius: 10px; padding: 20px; box-shadow: 0 4px 15px rgba(0,0,0,0.2); text-align: center;">
        <h3 style="color: green;">✅ ¡Registrado con éxito!</h3>
        <p>Los datos de tu mascota han sido guardados.</p>
        <form method="dialog">
            <button style="padding: 5px 20px; cursor: pointer;">Aceptar</button>
        </form>
    </dialog>

</body>
</html>
