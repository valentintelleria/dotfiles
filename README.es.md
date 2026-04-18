# 🧩 Dotfiles de Hyprland

🌍 Idioma: **Español** | [English](README.md)

Configuración de Hyprland con múltiples temas y personalización del entorno.

---

## 📸 Preview (Field)

![Field Desktop](previews/Field/fieldP1.png)
![Field Launcher](previews/Field/fieldP2.png)

---

## 🎨 Temas

El repositorio incluye tres configuraciones:

* **Field** → estilo limpio con fondo natural
* **Blue** → entorno oscuro y minimalista
* **Minimal** → configuración liviana y básica

Cada tema incluye:

* Hyprland
* Waybar
* Kitty
* Wofi

---

## 📸 Otros temas

### 🌙 Blue

![Blue Desktop](previews/Blue/blueP1.png)
![Blue Launcher](previews/Blue/blueP2.png)

---

### ⚪ Minimal

![Minimal Desktop](previews/Minimal/minimalP1.png)
![Minimal Launcher](previews/Minimal/minimalP2.png)

---

## ⌨️ Atajos de teclado

| Tecla               | Acción                    |
| ------------------- | ------------------------- |
| mod + Q             | abrir terminal            |
| mod + R             | abrir launcher (wofi)     |
| mod + E             | abrir gestor de archivos  |
| mod + C             | cerrar ventana            |
| mod + V             | alternar flotante         |
| mod + F             | pantalla completa         |
| mod + flechas       | mover foco                |
| mod + [1–0]         | cambiar workspace         |
| mod + shift + [1–0] | mover ventana a workspace |
| mod + mouse         | mover/redimensionar       |
| mod + P             | screenshot (pantalla)     |
| mod + shift + P     | screenshot (región)       |
| mod + U             | reiniciar waybar          |
| mod + M             | salir                     |

---

## ⚙️ Uso

Clonar el repositorio:

```bash id="es1"
git clone https://github.com/valentintelleria/dotfiles
cd dotfiles
```

Copiar el tema en `~/.config`:

```bash id="es2"
cp -r themes/Field/* ~/.config/
```

(Cambiar `Field` por `Blue` o `Minimal`)

---

## 🧠 Notas

* Configuración personal, puede requerir ajustes
* Algunas rutas dependen del sistema (monitor, wallpapers, etc.)
