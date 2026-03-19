# Vista de Contexto

Este diagrama muestra cómo interactúa el sistema.

```mermaid
graph TD
    Usuario[Usuario] -->|Usa| Sistema[Sistema Web]
    Sistema -->|Consulta| BD[Base de Datos]
    Sistema -->|Conecta| API[API Externa]


---

## 🧠 EXPLICACIÓN (para que entiendas)

Esto significa:

- `graph TD` → el diagrama va de arriba hacia abajo  
- `Usuario --> Sistema` → el usuario usa el sistema  
- `Sistema --> BD` → el sistema consulta la base de datos  
- `Sistema --> API` → el sistema se conecta a algo externo  

👉 Ya estás haciendo un **diagrama tipo C4 básico**

---

# 💾 PARTE 3: GUARDAR (MUY IMPORTANTE)

Baja hasta abajo de la página y verás:

👉 **Commit changes**

Haz esto:

1. No cambies nada
2. Solo da click en:

👉 **Commit changes**

---

# ✅ PARTE 4: VERIFICAR

Después de guardar:

1. Verás el archivo ya creado  
2. Debe llamarse:

👉 `contexto.md`

---

# ⚠️ MUY IMPORTANTE (ERROR COMÚN)

👉 Puede que NO veas el diagrama como dibujo todavía  
👉 Solo verás el código

✔ Eso es NORMAL  
✔ El diagrama se verá cuando activemos GitHub Pages (paso 6)

---

# 🧪 MINI PRUEBA (OPCIONAL)

Si quieres probar que sí funciona, edita otra vez el archivo:

1. Click en el lápiz ✏️ (editar)
2. Agrega esta línea abajo:

```mermaid
Admin --> Sistema


